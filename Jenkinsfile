pipeline {
    agent any
    
    stages {
        
        stage('github-clone') {
            steps {
                git branch: 'main', credentialsId: 'jenkins_key', url: 'git@github.com:ino214/docker-react-app.git'
            }
        }
        
   		// stage...
   	}
}
