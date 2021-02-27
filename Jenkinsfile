pipeline {
  environment {
    imagename = "raja565/dockertest"
    registryCredential = 'Rajagit565'
    dockerImage = ''
  }
  agent any
  stages {
    stage('Cloning Git') {
      steps {
        git([url: 'https://github.com/raja12345678/data-hub.git', branch: 'master', credentialsId: 'gitId'])

      }
    }
    stage('Building image') {
      steps{
        echo "it is working ......."
      }
    }
    

      }
   }
 