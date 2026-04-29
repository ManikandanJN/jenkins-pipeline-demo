pipeline {
    agent any

    tools {
        nodejs 'NodeJS' // Name configured in Jenkins Global Tool Configuration
    }

    stages {
        // stage('Checkout SCM') {
        //     steps {
        //         // If Jenkins job is already configured with SCM, this works:
        //         checkout scm
        //     }
        // }

        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Build') {
            steps {
                sh 'npm run build'
            }
        }

        stage('Run Dev Server') {
            steps {
                sh 'npm run dev'
            }
        }
    }
}