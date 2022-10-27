pipeline {
    agent any
	
	environment {
		env.PATH = 'c:\\Windows\\System32;'
	}
    stages {
        stage('git repo & clean') {
            steps {
                bat 'echo Intial setup'
            }
        }
        stage('install') {
            steps {
                bat 'echo Hello Install'
            }
        }
        stage('test') {
            steps {
                bat 'echo Hello Test'
            }
        }
        stage('package') {
            steps {
                bat 'echo Hello Package'
            }
        }
    }
}