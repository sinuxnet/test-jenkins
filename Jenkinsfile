pipeline {
    agent docker

    stages {
        stage('Test_1') {
            steps {
                echo 'Test_1'
                sh "env"
            }
         }
        stage('Test_2') {
            steps {
                echo 'Test_2'
                sh "ls -laht"
            }
         }
        stage('Test_3') {
            steps {
                echo 'Test_3'
            }
        }
    }
}
