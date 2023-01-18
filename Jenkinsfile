pipeline {
    agent any

    stages{
        stage("create zip file"){
            steps{
               
           sh 'zip middlewaereScript-${BUILD_NUMBER}.zip *  --exclude Jenkinsfile README.md '  
            
            }
        }
        
    }
}