pipeline{
	agent any
	stages{
		stage('BUILD'){
			steps{
				echo 'This Is the Build Steps';
				sh 'cd /home/deploy ';
				sh 'ls -l';
				}
			}
		stage('DEPLOY'){
			steps{
				echo 'This is the deploy step';
			}
				}

		}
}