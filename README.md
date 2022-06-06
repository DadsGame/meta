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

# Run local

Follow the Readme in the following repository
* [https://github.com/DadsGame/gametracker](https://github.com/DadsGame/gametracker)
* [https://github.com/DadsGame/backtoback](https://github.com/DadsGame/backtoback)
* [https://github.com/DadsGame/front](https://github.com/DadsGame/front)

# Versioning

* We do use the semver standard to version our app

# ADR

* We shall make keep track and make ADRs when there's a big software or architectural decision

# Useful links

* [Gitmoji](https://gitmoji.dev)
* [Semver](https://semver.org)
* [DB Diagram](https://dbdiagram.io/d/620bbbb6485e433543b6a6a7)
* [UI Mockup](https://www.figma.com/file/qYoF81Ty79jiHSsxjcYx6Z/Disney-Plush%2B-(Community)?node-id=0%3A1)

### Authors

* [@Galimede](https://github.com/Galimede) (Mathieu Degand)
* [@Skiadram](https://github.com/Skiadram) (Neel Coffin)

### Work distribution
| **Repository** | **Neel** | **Mathieu** |
|----------------|----------|-------------|
| back to back   | 0        | 100         |
| gametracker    | 65       | 35          |
| front          | 50       | 50          |
