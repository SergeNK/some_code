pipeline {
  agent any
  triggers {
   cron('H/7 * * * *')
  }
  stages {
    stage('echo') {
      steps {
        echo 'hello second message from the trigger'
      }
    }

  }
}
