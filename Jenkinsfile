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
               bat  'dir' 
            }
        }
        stage('print show fils') {
            steps {
              python hello.py
            }
        }
    }
}
