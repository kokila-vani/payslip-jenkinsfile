pipeline {
    agent any 
    tools {
        maven 'localmaven' 
    }
    stages {
        stage('BUILD') {
            steps {
                build 'spring1-payslip'
            }
        }
        stage('TEST'){
            steps{
                build 'spring1-test'
            }
        }
        stage('DEPLOY'){
            steps{
                build 'spring1-deploy'
            }
        }
    }
}
        
