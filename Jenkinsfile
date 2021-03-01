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
    
    stage('git checkout'){
        steps{
            git branch: 'Master', credentialsId: '8748bc1b-971c-4a2f-a360-f682c54ab2f6', url: 'https://github.com/farmerstest/INFORMATICA.git'
        }
}
}
}
