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
        sh '''hostname
'''
        sh '''whoami
'''
        sh 'sleep 20'
      }
    }
  }
}