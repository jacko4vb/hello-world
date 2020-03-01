pipeline {
  agent ecs{
    inheritFrom 'linux-java'
  }
  stages {
    stage('build') {
      steps {
        sh 'echo \'hello world\''
      }
    }

  }
}
