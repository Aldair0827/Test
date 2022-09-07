pipeline {
  agent {
    docker {
      image 'node:12'
      args '--network jenkins-blue-ocean-tutorial-mynet'
    }

  }
  stages {
    stage('Build ') {
      steps {
        sh 'sh \'echo "hola mundo"\''
      }
    }

  }
}