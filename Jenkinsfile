#!/usr/bin/env groovy

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo Building...'
                echo 'Test trigger finally'
            }
        }
        stage('Test') {
            steps {
                sh 'echo Testing...'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo Deploying...'
            }
        }
    }
}
