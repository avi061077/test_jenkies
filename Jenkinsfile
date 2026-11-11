properties([pipelineTriggers([cron('* * * * 1')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('show fils') {
            steps {
              sh 'ls -ltr'
            }
        }
        stage('print show fils') {
            steps {
            sh 'python3 hello.py'
            }
        }
    }
}
