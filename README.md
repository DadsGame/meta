# Description
A long time ago in a galaxy away, far far away there was a dad who loved playing video games. 
To keep track of the games he played, finished or not he kept a record of all of them in an excel file where he put every game he has done and the state he has left it in (started, won’t finish, finished) and if he bought it the price point at the time being and the amount the game was sold so that he could buy another game. To improve readability the games were separated into pages representing the platform of the game. His son was aware of this excel file, but he was also a student in computer science and thought it would be cool to automate some things and put other features on the table so that it doesn’t only replace the excel file. This story now is yet to come.


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

App is deployed on Clever Cloud at [https://app-a44cee5f-7e8d-476f-b6ce-16a019ac35c7.cleverapps.io/](https://app-a44cee5f-7e8d-476f-b6ce-16a019ac35c7.cleverapps.io/).

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
