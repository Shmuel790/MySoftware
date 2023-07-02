pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'python click.py'
                sh 'python welcome.py'
            }
        }
    }
}
