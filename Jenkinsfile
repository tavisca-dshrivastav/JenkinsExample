pipeline{
    agent {
        dockerfile true
    }
    stages{
        stage('example'){
            script{
                echo 'Hello world'
                docker.build('hello')
            }
        }
    }
}