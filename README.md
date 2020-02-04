# HPotter Spring 2020

## Process Details

### Team repos
* This team's **official** repositories are the org level repos at [HPotter-Spring-2020](https://github.com/HPotter-Spring-2020)
* Each repo has at least two branches `master` and `dev`
  * `master` has code ready to be released outside the team
  * `dev` had code ready to be release to the rest of the team
  * Only `dev` is merged to `master` via pull request with review

### Working with team repos
* Use `upstream` as the remote name for official team remotes
  * `git remote rename <whatever org remote is named> upstream`
  * For example: `git remote rename origin upstream`
* Team members work on their own forks of HPotter-Spring-2020 repos
* Code enters HPotter-Spring-2020 repos **only by pull request** with review and approval by at least one other team member
* When feasible, branch names on personal forks should start with the Jira issue (e.g. `HS-4-telnet`) to tie code to tracked work

### Pull requests
* Merge or rebase `orgRepo/dev` -> `myFork/personal-branch`
* Resolve any conflicts on your personal branch 
* Open pull request from `myFork/personal-branch` -> `orgRepo/dev`
* Add at least one reviewer from the team
* You may not merge your own pull request (under normal circumstances)


## Team Members
* Tanner Madsen | tmadsen4@msudenver.edu
* Kenji Morizono | kmorizon@msudenver.edu
* Judith Escobar | jsaenzes@msudenver.edu
* Megan Horton | mhorto17@msudenver.edu
* Joshua Brown | jbrow260@msudenver.edu
* Emily Berger | eberger5@msudenver.edu
* Evan Birt | ebirt@msudenver.edu
* Jon Bowen | jbowen10@msudenver.edu

## Technologies
* [Jira](https://gouda.msudenver.edu/jira/browse/HS)
* [Slack](https://drb80.slack.com/)
* Travis CI
* Codecov
