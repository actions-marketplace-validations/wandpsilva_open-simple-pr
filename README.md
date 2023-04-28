# Composite action

This is a simple action to create a pull request.

## Inputs

## `branch-origin`

**Required** 

The branch origin of the pull request.

## `branch-target`

**Required** 

The target branch for the pull request.

## `title`

**Optional** 

The title of the pull request.

## `body`

**Optional** 

The body of the pull request.


## Example usage

    uses: wandpsilva/open-pr@master
    with:
      branch-origin: 'develop'
      branch-target: 'main'
      title: 'my pull request'
      body: 'body of my pull request'