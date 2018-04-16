pipeline {
	agent any
	stages {
		stage('example'){
			steps {
				echo 'hello world'
				sh 'echo myCustomEnvVar = $myCustomEnvVar'
			}
		}
	}
}
