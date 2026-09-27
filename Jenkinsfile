pipeline {
    agent any
    stages {
        stage('Checkout') { steps { echo 'Code checked out from GitHub' } }
        stage('Build')    { steps { bat 'dir' } }
        stage('Test')     { steps { echo 'Running tests...' } }
    }
}
