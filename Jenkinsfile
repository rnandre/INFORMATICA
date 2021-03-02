pipeline {
    
    agent any
    stages{
        
   
        stage('Build') {
            steps {
                echo 'Building..'
                echo 'webhookTest'
                echo 'update in feature branch'

                echo "${currentBuild.fullProjectName}"
                echo "${currentBuild.fullDisplayName}"
                echo 'change in main branch again'

                echo 'test1'
                echo 'this if from feature_demo1'

            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    
    
}
}

