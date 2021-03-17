pipeline {
  agent {
    docker {
      image 'hello-world'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'curl 127.0.0.1'
      }
    }

  }
}