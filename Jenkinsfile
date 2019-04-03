pipeline {
  agent any
  stages {
    stage('Create RG') {
      steps {
        sh '''az login -u user10@kiddcorp.com -p SBUX1234!
az group create -n table5akgrg2 -l uksouth'''
      }
    }
  }
}