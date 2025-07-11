pipeline{
    agent {
        label 'java-slave'
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
