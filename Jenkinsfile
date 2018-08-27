pipeline {
  agent any
    triggers {
        eventTrigger simpleMatch("Frobulate")
    }
  stages {
    stage('Received frobulate') {
      steps {
        echo 'Received a Frobulate event'
      }
    }
  }
}
