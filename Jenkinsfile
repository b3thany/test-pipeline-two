pipeline {
  agent any
  stages {
    stage('Received an event') {
      steps {
        echo 'I just received a Testing Completed! event'
      }
    }
  }
  triggers {
    eventTrigger(simpleMatch('Testing Completed!'))
  }
}