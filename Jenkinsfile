pipeline {
  agent none
  
  stages {
    stage('build') {
      agent {
        ecs {
             inheritFrom 'linux-java'
        }
      }
      steps {
        sh 'echo \'hello world\''
      }
    }

  }
}
