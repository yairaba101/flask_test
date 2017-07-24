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
'''
        sh '''echo hostname
'''
        sh '''echo whoami
'''
        sh 'sleep 20'
      }
    }
  }
}