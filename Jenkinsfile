pipeline {
  agent any
  
stages {
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