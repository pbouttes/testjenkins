pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                echo 'Building stage' 
            }
        }
        stage('Test'){
            steps {
                echo 'Testing stage' 
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying stage'
            }
        }
    }
}