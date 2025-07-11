pipeline{
    agent {
        label 'java-slave'
    }
    tools{
        maven 'maven-3.9.5'
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
