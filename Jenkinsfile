pipeline {
  agent {
    node {
      label 'docker-slave'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh '''echo "test"
echo hostname
echo whoami
sleep 20'''
      }
    }
  }
}