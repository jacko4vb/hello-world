pipeline {
  agent none
  
  stages {
    stage('build') {
      agent {
        ecs{
        }
      }
      steps {
        sh 'echo \'hello world\''
      }
    }

  }
}
