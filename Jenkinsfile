pipeline{
    agent {
        dockerfile true
    }
    stages{
        stage('example'){
            steps{
                echo 'Hello world'
                docker.build('hello')
            }
        }
    }
}