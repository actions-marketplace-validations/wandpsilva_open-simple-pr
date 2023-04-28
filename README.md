# Composite action

This is a simple action to create a pull request.

## Inputs

## `branch`

**Required** 

The branch target for the pull request.

## `title`

**Optional** 

The title of the pull request.

## `body`

**Optional** 

The body of the pull request.


## Example usage

    uses: wandpsilva/open-pr@master
    with:
      branch: 'develop'
      title: 'my pull request'
      body: 'body of my pull request'