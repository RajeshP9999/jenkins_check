pipeline {
    agent any

    stages {
        stage('git clone') {
            steps {
                git 'https://github.com/RajeshP9999/jenkins_check.git'
            }
        }
       
        stage('pip'){
            steps{
                sh 'python3 -m pip install -r requirements.txt'
            }
        }
         stage('checking python version'){
            steps{
                sh 'python3 --version'
            }
        }
    }
}
