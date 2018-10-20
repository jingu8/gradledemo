pipeline {
  agent any
  stages {
    stage('Print') {
      steps {
        echo 'Gradle Demo'
      }
    }
    stage('source') {
      steps {
        build 'gradle build'
      }
    }
  }
}