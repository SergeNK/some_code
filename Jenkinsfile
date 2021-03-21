pipeline {
  agent any
  triggers {
   cron('H/15 * * * *')
  }
  stages {
    stage('echo') {
      steps {
        echo 'hello second message from the trigger'
      }
    }

  }
}
