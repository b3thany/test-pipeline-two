pipeline {
  agent any
    triggers {
        eventTrigger simpleMatch("frobulate")
    }
  stages {
    stage('Received frobulate') {
      steps {
        echo 'Received a frobulate event'
      }
    }
  }
}
