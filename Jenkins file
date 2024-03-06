pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                cleanWs()
                echo 'Hello World'
		        sh 'mkdir abc'
	            sh 'ls -lart'
		        sh 'pwd'
            }
        }
	
    }
}
