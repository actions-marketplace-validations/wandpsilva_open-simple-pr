# wandpsilva/simple-open-pr action

Simple action to open pull requests automatically.

# **Inputs**

## `branch-origin`

**Optional** 

The branch origin of the pull request, if not specified, the branch calling this action will be assumed.

## `target-branch`

**Optional** 

The target branch for the pull request, if not specified, the branch main will be assumed.

## `title`

**Optional** 

The title of the pull request.

## `body`

**Optional** 

The body of the pull request.


# **Usage**
```yaml
    uses: actions/checkout@v3
    uses: wandpsilva/open-simple-pr@v1
    with:
      branch-origin: 'develop'
      target-branch: 'main'
      title: 'my pull request'
      body: 'body of my pull request'
```

you can specify the branch-origin by using github actions environment variables:
```yaml
    uses: actions/checkout@v3
    uses: wandpsilva/open-simple-pr@v1
    with:
      branch-origin: ${{ github.ref_name }}
      target-branch: 'main'
      title: 'my pull request'
      body: 'body of my pull request'
```

you can also omit all the inputs fields:
```yaml
    uses: actions/checkout@v3
    uses: wandpsilva/open-simple-pr@v1
```

**Do not forget to checkout your code before calling this action by using actions/checkout action.**
