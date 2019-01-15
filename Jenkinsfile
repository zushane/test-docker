#!groovy

pipeline {
	agent { 
		docker { 
			image 'centos:7' 
		}  
	}
//	agent any 

	stages {
		stage ( 'test' ) {
			steps {
				echo 'Hello, world!'	
			}
		}
	}
}
