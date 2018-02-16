pipeline {
  agent {
    node {
      label 'mac'
    }
   
    
  }
   tools{
      maven 'maven'
    }
  stages {
    stage('TestStage') {
      steps {
       sh 'mvn -version'
      }
    }
  }
}
