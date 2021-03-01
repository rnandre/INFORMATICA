pipeline {
    agent any

   
        stage('Build') {
            steps {
                echo 'Building..'
                echo 'webhookTest'
                echo 'update in feature branch'
                echo "${currentBuild.fullProjectName}"
                echo "${currentBuild.fullDisplayName}"
                echo 'change in main branch'
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
