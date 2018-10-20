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
        git(url: 'https://github.com/jingu8/gradledemo', branch: 'main', changelog: true, poll: true)
      }
    }
  }
}