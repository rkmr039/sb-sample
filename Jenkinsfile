pipeline{
    agent any
    tools{
        maven 'MAVEN'
    }
    stages{
        stage("SCM Checkout"){
            steps{
            git 'https://github.com/rkmr039/SpringBoot.git'
            }
        }
        stage("Maven Build"){
            steps{
                bat 'mvn clean package'
            }
        }
    }
}