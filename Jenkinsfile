pipeline{
    agent any
    stages {
        stage('Build') {
            steps {
                echo "This is example for build triggers using github hook tst on nov-15"
                echo "**** next one is linux whoami command ***"
                sh "whoami"
                echo "This is to test poll SCM i sheduled to check for every minute , every hour , every daya, every month , every Yesar"
                echo "***** ### **"
                echo "Poll Scm is opposite to gitbub hook it jenkins will check for commit and push  based given shedule"
                echo "bye"
            }
        }
    }
    post {
        success {
            echo "I am post step of deployement..."
        }
    }

}
