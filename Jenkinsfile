pipeline {
	agent {
		Dockerfile true
	}
	stages {
		stage('example'){
			steps {
				echo 'hello world'
				sh 'echo myCustomEnvVar = $myCustomEnvVar'
			}
		}
	}
}
