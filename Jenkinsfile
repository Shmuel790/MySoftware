pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/Shmuel790/MySoftware.git'
                sh 'python click.py'
                sh 'python welcome.py'
            }
        }
    }
}
