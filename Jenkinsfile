pipeline {
    any agent 
    tools {
        nodejs "NodeJS"
    }
    stages {
        stage('Scm Checkout') {
            steps {
                checkout scm
            }
        }
      stage('build'){
        steps {
          sh "npm install"
        }
    }
      stage('test'){
        steps {
           sh "npm test"
        }
      } 
          
}
