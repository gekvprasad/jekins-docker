pipeline {
	agent{
		label 'slave'
	}
	stages{
		stage('Hello'){
			steps{
				sh 'Java -version'
				echo "Get working Directory"
				sh 'pwd'
			}
		}
	}
}
