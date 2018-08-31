github-flow
===========

git flow esque helpers, designed with github in mind.

Installation
------------

To install, run the installation script:

```
curl https://raw.githubusercontent.com/hsnks100/github-flow/master/install.sh | $(which bash)

```

To update, run the install script again.

To install or update outside the default directory, pass a folder as the first parameter to bash.

Usage
-----

Usage is very similar to git-flow


`git hub-feature start <feature>` Begin working on a new feature.

`git hub-feature update [feature]` Bring master branch up to date, and rebase `feature` off master.

`git hub-feature publish [feature]` Push changes on `feature` to `origin` repository.


All commands with `[feature]` either take a parameter to specify the branch, or work off the current (non-`master`) branch.


