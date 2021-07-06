pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        echo 'hello from the trigger'
      }
    }

    stage('Another echo') {
      steps {
        sleep 3
      }
    }

  }
  triggers {
    cron('H/15 * * * *')
  }
}