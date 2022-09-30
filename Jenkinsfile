pipeline{
    agent any
    stages{
        stage('version'){
            steps{
                sh 'python3 --version'
            }
        }
        stage('pythonfile'){
            steps{
                sh 'python3 pythonfile.py'
            }
        }
    }
}