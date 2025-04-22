pipeline {
    agent any

    stages {
        stage('Dev') {
            steps {
                echo 'DEV ENV DEPLOYED'
                powershell'''
                $name="Aman"
                Write-Host "Mellow $name"
                
                '''
            }
        }
        stage('SIT'){
            steps{
                echo 'SIT ENV DEPLOYED'
            }
        }
        stage('UAT'){
            steps{
                echo 'UAT ENV DEPLOYED'
            }
        }
        stage('PROD'){
            steps{
                echo 'PROD ENV DEPLOYING'
                script{
                 powershell '''
                  node demo.js
                 '''
                    
                }

            }
        }
    }
}

