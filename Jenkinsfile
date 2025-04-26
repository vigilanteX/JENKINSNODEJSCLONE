pipeline {
    agent any
    stages {
        stage("dev") {
            steps {
                powershell '''Write-Host "DEV BUILD STARTED"'''
            }
        }
        stage("sit") {
            steps {
                powershell '''Write-Host "SIT BUILD STARTED"'''
            }
        }
        stage("uat") {
            steps {
                powershell '''Write-Host "UAT BUILD STARTED"'''
            }
        }
    }
}
