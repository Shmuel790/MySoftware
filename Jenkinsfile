pipeline {
    agent any

    stages {
        stage('Click') {
            steps {
                sh 'python click.py'
            }
        }
        stage('Welcome') {
            steps {
                sh 'python welcome.py'
            }
        }
    }
}
