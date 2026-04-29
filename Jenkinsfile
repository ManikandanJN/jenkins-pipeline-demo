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
                bat 'npm install'
            }
        }

        stage('Build') {
            steps {
                bat 'npm run build'
            }
        }

        // stage('Run Dev Server') {
        //     steps {
        //         bat 'npm run dev'
        //     }
        // }
    }
}