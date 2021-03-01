pipeline {
    agent any

    stages {
         stage('Git chekout'){
               git branch: '$Branch', credentialsId: 'git-login', poll: false, url: 'https://github.com/farmerstest/INFORMATICA.git'
    }
        stage('Build') {
            steps {
                echo 'Building..'
                echo 'webhookTest'
                echo 'update in feature branch'
                echo "${currentBuild.fullProjectName}"
                echo "${currentBuild.fullDisplayName}"
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
