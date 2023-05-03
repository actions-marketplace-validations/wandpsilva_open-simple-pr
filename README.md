# wandpsilva/simple-open-pr action

This is a simple action to open pull requests.

# **Inputs**

## `branch-origin`

**Required** 

The branch origin of the pull request.

## `target-branch`

**Required** 

The target branch for the pull request.

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