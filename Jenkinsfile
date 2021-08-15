pipeline{
    agent any
    tools{
        jdk 'jdk11'
        maven 'maven3'
    }
    stages{
        stage('Compile'){
            steps{
                sh 'mvn compile'
            }
        }
    }
    stages{
        stage('Test'){
            steps{
                sh 'mvn test'
            }
        }
    }
    stages{
        stage('Package'){
            steps{
                sh 'mvn package'
            }
        }
    }
}