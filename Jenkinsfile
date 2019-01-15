#!groovy

pipeline {
	agent { 
		docker { 
			label 'Default'
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
