pipeline {
  agent {
    node {
      label 'mac'
    }
    
  }
  stages {
    stage('TestStage') {
      steps {
        sh '''mvn version
'''
      }
    }
  }
}