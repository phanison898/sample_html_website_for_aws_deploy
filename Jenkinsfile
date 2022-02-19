pipeline {
	agent any
	stages {
		stage("Build") {
			steps {
			echo "There is nothing to build"
			}
		}
		stage("Test") {
			steps {
			echo "There is nothing to tes"
			}
		}
		stage("Deploy") {
			steps {
			sh '''#!/bin/bash
			        cd ~
				ls -la
                		cd /var/www/html
				sudo rm -rf *
				sudo git clone https://github.com/phanison898/sample_html_website_for_aws_deploy.git
				sudo mv sample_html_website_for_aws_deploy/* .
         		'''
			}
		}
	}
}
