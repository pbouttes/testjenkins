pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                bat echo Building stage
            }
        }
        stage('Test'){
            steps {
                bat 'echo Testing stage' 
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying stage'
            }
        }
    }
}