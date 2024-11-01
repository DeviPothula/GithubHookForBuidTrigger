pipeline{
    agent any
    stages {
        stage('Build') {
            steps {
                echo "This is example for build triggers using github hook"
                echo "**** next one is linux whoami command ***"
                sh "whoami"
            }
        }
    }
    post {
        success {
            echo "I am post step of deployement..."
        }
    }

}