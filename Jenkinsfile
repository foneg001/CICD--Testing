pipeline {
    agent any 
    parameters {
			choice(name: 'VERSION', choices: ['1.1.1','1.2.1','1.2.3'], description: 'process to be deployed')
					
			}
    
    stages {
        stage('Build') {
            steps {
                echo 'Hello world!' 
            }
        }
        stage('Test') {
            steps {
                echo 'Hello world!2' 
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello world!3' 
		    echo "guy esta a deployar ${params.VERSION}"
            }
        }
    }
}
