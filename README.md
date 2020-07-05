# AndroidTemplate
Template repository for Android projects

## Tools Installed
Commitlint
Danger
Dependabot

## Get Started
run `npm install` to install the commit linting tools.
If using Jacoco, add `jacoco_version` to your root `build.gradle`.

## Configure
To configure Danger, go into the `DangerFile` and update any relevant settings. Currently it will only run for issues that Detekt raises up.
To cofigure Dependabot, go to `.github/dependabot.yml` and update any relevant settings.