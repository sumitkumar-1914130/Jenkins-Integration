pipeline{
    agent any
    stages{
        stage('version'){
            steps{
                sh 'python --version'
            }
        }
        stage('pythonfile'){
            steps{
                sh 'python pythonfile.py'
            }
        }
    }
}
