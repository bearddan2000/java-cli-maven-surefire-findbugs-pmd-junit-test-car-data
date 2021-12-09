# java-cli-maven-surefire-findbugs-pmd-junit-test-car-data

## Description
Analyze source code for potential bugs.
A POC for sprimg app using JUnit
framework with surefire and
pmd plugins.

## Tech stack
- java
- maven
	- findbugs
  - spring
  - junit
  - surefire
  - pmd

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- pmd report found at bin/target/site
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://github.com/eugenp/tutorials/tree/master/maven-modules/maven-integration-test)
