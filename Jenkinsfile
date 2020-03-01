pipeline {
  agent none
  
  stages {
    stage('build') {
      agent {
        ecs {
             label 'linux-java'
        }
      }
      steps {
        sh 'echo \'hello world\''
      }
    }

  }
}
