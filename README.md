# Commit and branches convention

## Commit

* We do use gitmoji to easily identify the purpose of the commit and for changelog purpose
* Each commit must start with the name of the feature in lowercase followed by a colon
* Then you shall put a description of your commit 

## Branches

* Each project must have a *develop* branch in addition to a main branch
* Each feature branch should be named as: > feature/name

When a feature is finished you shall create a pull request to the develop branch.
The develop branch purpose is for pre-prod environment and testing.
The main branch will be used for releases.

# Deployment

App deployment will be made on [Clever Cloud](https://clever-cloud.com).

# Versioning

* We do use the semver standard to version our app

# Useful links

* [Gitmoji](https://gitmoji.dev)
* [Semver](https://semver.org)
