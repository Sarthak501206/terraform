pipeline {
    agent any

    stages {
        stage('Pull Code') {
            steps {
                echo 'Pulling code from GitHub...'
            }
        }
        stage('Run Script') {
            steps {
                sh './terraform/hello.sh'
            }
        }
    }
}
