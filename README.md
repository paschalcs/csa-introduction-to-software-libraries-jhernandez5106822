[![Build Status](https://travis-ci.com/wilmol/java-gradle-template.svg?branch=master)](https://travis-ci.com/wilmol/java-gradle-template)
[![codecov](https://codecov.io/gh/wilmol/java-gradle-template/branch/master/graph/badge.svg)](https://codecov.io/gh/wilmol/java-gradle-template)
[![GitHub issues](https://img.shields.io/github/issues/wilmol/java-gradle-template.svg)](https://github.com/wilmol/java-gradle-template/issues)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/wilmol/java-gradle-template.svg)](https://github.com/wilmol/java-gradle-template/pulls/)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/wilmol/java-gradle-template/graphs/commit-activity)
[![GitHub license](https://img.shields.io/github/license/wilmol/java-gradle-template.svg)](https://github.com/wilmol/java-gradle-template/blob/master/LICENSE)

# java-gradle-template
template repository for Java using Gradle build tool, Travis CI, Codecov and more

## Usage
* Just go to: https://github.com/wilmol/java-gradle-template/generate
    * This will prompt you to create a new repository with all the files setup
* Rename the root project (currently `java-gradle-template`) and group (currently `com.wilmol`) to your liking 
* Create your README
* Delete anything you won't use (sub projects, dependencies etc.)

## Features
* Java 11
* Gradle 5+
  * Multi-project builds
* [Travis CI](https://travis-ci.com/) integration
* [Codecov](https://codecov.io/) integration
* [Spotless](https://github.com/diffplug/spotless) integration

## WIP/Future
* [Error Prone](https://errorprone.info/) integration
  * Currently has issues with Gradle

## Build
```
./gradlew spotlessApply clean build
```
