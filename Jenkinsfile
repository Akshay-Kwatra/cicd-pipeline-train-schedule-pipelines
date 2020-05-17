pipeline {
	agent any
	stages {
        stage('Build') {
		steps {
                 echo 'Automated gradle build'
                 sh './gradlew build --no-daemon'
                 archiveArtifacts artifacts: 'dist/trainSchedule.zip'
	}
    }
  }

}
