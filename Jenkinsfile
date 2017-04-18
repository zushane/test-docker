#!groovy

pipeline {
	agent { docker { image 'centos:7' }  }

	stages {
		stage ( 'test' ) {
			steps {
				echo 'Hello, world!'	
			}
		}
	}
}
