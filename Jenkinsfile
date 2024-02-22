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
 
    stage('Install Dep'){
        steps{
            sh 'npm install '
        }
    }
    stage('Build Angular App') {
            steps {
                sh 'npm run build'
            }
        }
    }

}