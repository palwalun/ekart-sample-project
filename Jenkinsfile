pipeline {
 agent any
  stages{
    stage('Checkout'){
	 steps{
	  git url: 'https://github.com/palwalun/ekart-sample-project.git',
	  branch: 'main'
	 }
	
	}
	stage ('Build app&image'){
	 docker build -t ekart-webapp .
	
	}
  
  
  
  }



}