pipeline {
  agent any
  stages {
    stage('Received Frobulate') {
      steps {
        echo 'Received a Frobulate event'
      }
    }
  }
  triggers {eventTrigger(simpleMatch('Frobulate'))}
}
