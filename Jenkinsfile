#!groovy

pipeline {
	agent any 

	stages {
		stage ( 'env' ) {
			agent any
			steps {
				sh 'env'
			}
		}
		stage ( 'test' ) {
			agent { 
				docker 'centos:7'  
			}
			steps {
				echo 'Hello, world!'	
			}
		}
	}
}
