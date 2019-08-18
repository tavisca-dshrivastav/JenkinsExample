pipeline{
    agent {
        dockerfile true
    }
    stages{
        stage('example'){
            steps{
                echo 'Hello world'
                sh 'docker build --tag=hello'
            }
        }
    }
}