pipeline {
	agent any
	stages {
		stage("Build") {
			steps {
			sh '''#!/bin/bash
                 echo $PATH 
         		'''
			}
		}
		stage("Test") {
			steps {
			echo "Testing ........."
			}
		}
		stage("Deploy") {
			steps {
			echo "Deploying ........."
			}
		}
	}
}
