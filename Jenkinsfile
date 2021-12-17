pipeline {
    agent any
    stages {
	stage('Pre-build'){
	    steps {
		echo 'Hello World!'
		}
	}
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
