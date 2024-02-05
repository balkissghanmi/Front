pipeline {
  agent any
  
stages {
    stage('Checkout GIT') {
      steps {
        git branch: 'main',
          credentialsId: 'test',
          url :'https://github.com/balkissghanmi/Front.git'
      }
     
    }
 
    stage('NPM INSTALL'){
        steps{
            sh 'npm install '
        }
    }
}
} 