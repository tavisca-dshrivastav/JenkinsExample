pipeline{
    agent {
        dockerfile true
    }
    stages{
        stage('example'){
            steps{
                echo 'Hello world'
                sh 'echo myCustomEnvVar = $myCustomEnvVar'
            }
        }
    }
}