pipeline {
    agent any
    tools {
        maven 'maven' 
    }
    stages {
      stage('Build') {
            steps {
                echo 'Building'
                sh 'mvn compile'
            }
        }
         stage('Unit test') {
            steps {
                echo 'Unit testing'
            }
        }
        stage('QA') {
            steps {
                echo 'QA'
            }
        }
        stage('Release') {
            steps {
                echo 'Releasing'
            }
        }


    }

