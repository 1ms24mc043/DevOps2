pipeline {
	agent any

	stages { 
		stage('Checkout') {
			steps {
				git branch: 'main', url: 'https://github.com/1ms24mc043/DevOps2'
			}
		}

		stage('Build') {
			steps {
				echo "Building..."
			}
		}

		stage('Test') {
			steps {
				echo "Testing///"
			}
		}
	}
}
