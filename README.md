# HPotter Spring 2020

## Process Details

### Team repos
* This team's **official** repositories are the org level repos at [HPotter-Spring-2020](https://github.com/HPotter-Spring-2020)
* Each repo has branches `dev`, `master`, and feature branches
  * Feature branches are created by team members
  * `dev` is the destination for feature branches. Feature braches are merged to `dev` via pull requests **with review**
  * `master` stays in sync with [Dr. Beaty's master branch](https://github.com/drsjb80/HPotter/tree/master). Our team only updates this branch by pulling from Dr. Beaty's master and pushing to our team master

### Working with team repos
* Work on the team repo. Do not create your own fork.
* Create feature branches from `dev`.
  1. `git checkout dev`
  1. `git pull origin dev`
  1. `git checkout -b hs-4-myFeatureBranchName` 
* When possible, start feature branch names with the associated Jira issue id (e.g. `hs-4-telnet`). This easily ties to branch to all the info about it on Jira. 
* Code moves from feature branches to `dev` **only by pull request** with review and approval by at least one other team member.

### Pull requests
* Code only enters `dev` via pull request.
* At least one other team member must review and approve pull requests before they can be merged.
* You may not merge your own pull request.
* Merging or rebasing to `dev` is suggested to spot conflicts before opening a PR. On the feature branch...
  * `git pull origin dev` OR
  * `git pull --rebase origin dev`
* Resolve any conflicts on your personal branch 

# General Info

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
* [Travis CI](https://travis-ci.org/HPotter-Spring-2020/HPotter)
* [Codecov](https://codecov.io/gh/HPotter-Spring-2020)
