pipeline{
    agent any
    tools{
        maven 'maven-3.9.5'
    }
    stages{
        stage('Maven'){
            steps{
                echo "This is Build stage"
                sh "mvn --version"
                // by deafult mavan 3.8.8
                // java 21
            }
        }
        stage('Tools'){
            tools{
                jdk 'JDK-17'
            }
            steps{
                echo "show maven version"
                sh "mvn --version"
            }
        }
    }
}
