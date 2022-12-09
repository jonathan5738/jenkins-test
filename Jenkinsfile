pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                sh 'this an hello word shell app'
                echo 'Hello World'
                echo 'Build number from jenkins is ${currentBuild.number}'
            }
        }
    }
}
