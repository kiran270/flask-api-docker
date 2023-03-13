pipeline {
	agent none
  stages {
    stage('Docker Build') {
    	agent any
      steps {
      	sh '''
	git clone https://github.com/kiran270/flask-api-docker.git
	cd flask-api-docker
	docker build -t flask-api-docker:latest .
	'''
      }
    }
  }
}
