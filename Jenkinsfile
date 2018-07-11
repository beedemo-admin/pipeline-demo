pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'we\'re building'
      }
    }
    stage('Test') {
      steps {
        echo 'We\'re testing...'
      }
    }
    stage('Notify') {
      steps {
        echo 'sending helloWorld'
        publishEvent simpleEvent('helloWorld')
      }
    }
  }
}