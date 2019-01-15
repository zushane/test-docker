#!groovy

pipeline {
	agent { 
		docker 'centos:7'  
	}
//	agent any 

	stages {
		stage ( 'env' ) {
			agent any
			steps {
				sh 'env'
			}
		}
		stage ( 'test' ) {
			steps {
				echo 'Hello, world!'	
			}
		}
	}
}
