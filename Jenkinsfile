pipeline {
  agent {
    node {
      label 'docker-slave'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'tar -zcvf flask_test.tar.gz flask_hello/'
      }
    }
  }
}