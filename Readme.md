# Contribution Guidelines

Hi! Thank you for taking the time to contribute to Flatjs!

In order to make the best use of both your time and that of the flatjs maintainers, please follow the guidelines in this document.

## Bug Fixes

If you would like to contribute a bugfix, please first create an issue detailing the bug, and also indicate that you intend to fix it. When creating commits, please follow the commit message format below.

## New Features

Again, please create a feature request detailing the functionality you intend to add, and state that you would like to implement it. When creating commits, please follow the commit message format below.

## Commit message format

This repo uses [Conventional Commits](https://www.conventionalcommits.org).

```
type(scope): Message in present tense
```
`type` may be one of:
* **feat** (new feature)
* **fix** (bug fix)
* **docs** (changes to documentation)
* **perf** (performance improvements)
* **style** (formatting, missing semi colons, etc; no code change)
* **refactor** (refactoring production code)
* **test** (adding missing tests, refactoring tests; no production code change)
* **chore** (updating build tasks etc; no production code change)

`scope` indicates the package affected by the commit:

* forge
* forge-babel-preset
* forge-plugin-multi-input
* fabricate
* evolve
* evolve-babel-preset
* forge-plugin-postcss
* forge-plugin-px2rpx
* etc.

If a commit affects more than one package, seperate them with a comma:

```
fix(forge,evolve): Fix the thing
```

If a commit applies to no particular package (e.g. a tooling change in the root package.json), the scope can be omitted.

#### Linting

Commit messages are linted on commit, so you'll know if your message is not quite right. 
