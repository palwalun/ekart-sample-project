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
	 steps{
	 docker build -t ekart-webapp .
	 }
	
	}
  
  
  
  }



}