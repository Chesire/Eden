# AndroidTemplate

Template repository to pre-configure Android projects with various tools.

## Tools

List of tools that will be installed or have configuration provided.  

* Commitlint  
* Danger  
* Dependabot  
* Jacoco  
* ktlint  
* Detekt  
* GitHub Actions  
* Bintray publishing  

## Get Started

* [ ] Run `npm install` to install the commit linting tools.  
* [ ] Add a GitHub secret for the Danger API key as `DANGER_API_TOKEN`.  
* [ ] Create an Android project.  
* [ ] Check file paths in the Dangerfile to ensure it checks the correct locations for reports.
* [ ] Update CONTRIBUTING.md.
* [ ] Update README.

### App

* [ ] Remove `com.jfrog.bintray.gradle:gradle-bintray-plugin` from build.gradle.
* [ ] Remove the examplepublish.gradle file.
* [ ] Remove the publish.gradle file.
* [ ] Remove the publish.yml GitHub action file.

### Library

* [ ] Add GitHub secrets for `BINTRAY_USER_ID` & `BINTRAY_API_KEY`.  
* [ ] Add Bintray publishing to the project, follow example gradle file.  

## Configure

* To ensure failed tests do not fail a build before we can report on results, add `testOptions { unitTests.all { setIgnoreFailures(true) } }` to the modules `build.gradle`.  

# Once repository is configured, delete this section.
 ============================================================================

# Project Name

> Description of the project
  
Badges

<!-- If Application
> Google Play Link
> Screenshots

## Features

## Tech Stack
-->

<!-- If Library
## Installation

## Usage example

## Configuration

-->

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING_URL_HERE) for details on how to contribute.

## License

Apache 2.0 - See [LICENSE](LICENSE_URL_HERE) for more information.
