pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "first line"'
                sh '''
                echo  "multiple line"
                ls
                who
                pwd
                '''
            }
        }
    }
}
