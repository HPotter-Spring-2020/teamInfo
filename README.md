# HPotter Spring 2020

## Process Details

### Team repos
* This team's **official** repositories are the org level repos at [HPotter-Spring-2020](https://github.com/HPotter-Spring-2020)
* Each repo has branches `dev`, `master`, and feature branches
  * Feature branches are created by team members
  * `dev` and `master` branches stay in sync with [Dr. Beaty's master branch](https://github.com/drsjb80/HPotter/tree/master). Our team only updates these branches by pulling from Dr. Beaty's dev and master and pushing to our team's dev and master

### Working with team repos
* Work on the team repo. Do not create your own fork.
* Create feature branches from `dev`.
  1. `git checkout dev`
  1. `git pull origin dev`
  1. `git checkout -b hs-4-myFeatureBranchName` 
* When possible, start feature branch names with the associated Jira issue id (e.g. `hs-4-telnet`). This easily ties branches to all the info about the issue on Jira. 
* Code moves from feature branches to `drsjb80/<remote>/dev` via pull request to be merged by Dr. Beaty
* After Dr. Beaty merges a pull requst, we must update the org branch to sync with `drsjb80/<remote>/dev`

### Pull requests
* Pull requests to `ourOrg/<repo>/dev` may be opened to allow the team to review before sending to Dr. Beaty.
* *HOWEVER*, pull requests to `ourOrg/<repo>/dev` should not be merged
* When confident the PR is ready for Dr. Beaty's review, open a PR to `drsjb80/<remote>/dev`
* If and when Dr. Beaty merges PRs to his repos, the changes are official. We need to:
  1. update `ourOrg/<repo>/<branch>` to reflect the offical changes
  1. Close the PR to `ourOrg/<repo>/<branch>` **without merging** (the code comes from Dr. Beaty's merge)
  1. Delete the feature branch from remote. The code is now safely in the official repo

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
* [Slack](https://drb80.slack.com/archives/CCJRBT03Z)
* [Travis CI](https://travis-ci.org/HPotter-Spring-2020/HPotter)
* [Codecov](https://codecov.io/gh/HPotter-Spring-2020)
