pipeline {
    agent any 
    stages {
        stage('Clone repo') { 
            steps {
	        	echo 'Cloning ...'
                	sh "git clone https://github.com/pabloccna/11-k8s-gitops"	
            }
        }
	stage('Build') { 
            steps {
		        echo 'Build....'
                	
           }
        }
	  stage('Deploy K8S') {
            steps {
            echo 'Deplpoyy.....'
            
            }
    }  
    
	post { 
        	always { 
            	cleanWs()
		}
        }
}
