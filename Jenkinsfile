pipeline {
  agent any
  stages {
    stage('Received Frobulate') {
      steps {
        echo 'Received a Frobulate event'
      }
    }
    stage('Raise Happify') {
      steps {
        script {
          publishEvent simpleEvent('Happify')
        }

      }
    }
  }
  triggers {
    eventTrigger(simpleMatch('Frobulate'))
  }
}