pipeline {
	agent any
        stage('Build') {
		steps {
                 echo 'Automated gradle build'
                 sh './gradlew build --no-daemon'
                 archiveArtifacts artifacts:: 'dist/trainSchedule.zip'
    }
  }

}
