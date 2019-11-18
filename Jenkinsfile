pipeline {
	agent any
		stages {
			/**INGFAVBANK-Frontend declarative Pipeline Job Build and Test stages **/
			stage('SCM Checkout') {
				steps {
					git url: 'https://github.com/amar5182/INGFAV_UI.git'
						}
								}
			stage('Build') {
				steps {
					sh"npm install"
					sh"npm run build"
							}
					}
				}
		}
		
