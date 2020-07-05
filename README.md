# AndroidTemplate
Template repository for Android projects

## Tools Installed
* Commitlint  
* Danger  
* Dependabot  

## Tools Configred
* Detekt  
* KtLint  

## Get Started
run `npm install` to install the commit linting tools.  
If using Jacoco, add `jacoco_version` to your root `build.gradle`.  

## Configure
To configure Danger, go into the `DangerFile` and update any relevant settings. Currently it will only run for issues that Detekt raises up.  
To configure Dependabot, go to `.github/dependabot.yml` and update any relevant settings.

## To Add
[Danger AndroidLint](https://github.com/loadsmart/danger-android_lint)  
[Danger JUnit](https://github.com/orta/danger-junit)  
[Danger KotlinDetekt](https://github.com/NFesquet/danger-kotlin_detekt)
