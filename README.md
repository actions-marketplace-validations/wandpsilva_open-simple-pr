# wandpsilva/simple-open-pr action

Simple action to open pull requests automatically.

# **Inputs**

## `branch-origin`

**Required** 

The branch origin of the pull request, if not specified, the branch calling this action will be assumed.

## `target-branch`

**Required** 

The target branch for the pull request, if not specified, the branch main will be assumed.

## `title`

**Optional** 

The title of the pull request.

## `body`

**Optional** 

The body of the pull request.


# **Usage**
```yaml
    uses: wandpsilva/open-simple-pr@master
    with:
      branch-origin: 'develop'
      branch-target: 'main'
      title: 'my pull request'
      body: 'body of my pull request'
```