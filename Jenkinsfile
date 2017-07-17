pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'tar -zcvf flask_test.tar.gz flask_hello/'
      }
    }
  }
}