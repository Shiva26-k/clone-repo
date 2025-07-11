pipeline{
    agent {
        label 'java-slave'
    }
    stages{
        stage('Build'){
            steps{
                timeout(time: 5 , unit: 'SECONDS'){
                 echo "Building the job"
                sleep 10 
                }
            }
        }
    }
}
