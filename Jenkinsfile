pipeline{
    agent {
        label 'java-slave'
    }
    tools{
        maven 'maven-3.8.9'
    }
    stages{
        stage('Maven'){
            steps{
                echo "This is Build stage"
                sh "mvn --version"
            }
        }
    }
}
