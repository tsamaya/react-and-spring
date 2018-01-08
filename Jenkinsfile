pipeline {
  agent any
  tools {
    nodejs 'node-8.9.0'
    gradle 'gradle-3.5.1'
    jdk 'jdk1.8'
  }
  stages {
    stage('Webpack Build') {
      steps {
        sh 'npm i'
        sh 'npm run webpack'
      }
    }
    stage('Gradle Build') {
      steps {
        // sh './gradlew build'
        sh 'gradle build'
      }
    }
  }
  triggers {
    pollSCM('* * * * 1-5')
  }
}
