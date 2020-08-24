pipeline {
  agent any
    
  tools {nodejs "Node 12.13.0"}
    
  stages {
        
    // stage('Cloning Git') {
    //   steps {
    //     git 'https://mcp-github.apps.carrier.com/Anudeep-Krishnadas/demo-app.git'
    //   }
    // }
        
    stage('Install dependencies') {
      steps {
        sh 'npm install'
      }
    }
     
    stage('Test') {
      steps {
         sh 'npm test'
      }
    }      
  }
}
