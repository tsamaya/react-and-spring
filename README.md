# React.js and Spring REST

This is a sample [springboot](https://projects.spring.io/spring-boot/) application using [ReactJS](https://reactjs.org/). The source code is coming from this tutorial:
https://spring.io/guides/tutorials/react-and-spring-data-rest/.

While the tutorial is using maven and a front-end plugin to build the react bundle file, this repository project is built with [webpack](https://webpack.js.org/) and [gradle](https://gradle.com).

This repository is also adding a [Jenkins pipeline](https://jenkins.io/doc/book/pipeline/) to build the project.

## Getting started

--TODO--

## Manual build

--TODO--

## Jenkins build

--TODO--

configure Tools in `Global Tool Configuration` accordingly with `Jenkins` file `tools` section:
```
tools {
  nodejs 'node-8.9.0'
  gradle 'gradle-3.5.1'
  jdk 'jdk1.8'
}
```
# Issues
Find a bug or want to request a new feature?  Please let me know by submitting an issue.

# Licensing
Licensed under the MIT License

A copy of the license is available in the repository's [LICENSE](LICENSE.md) file.
