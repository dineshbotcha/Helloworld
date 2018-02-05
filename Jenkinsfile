pipeline {
    agent any
    agent { docker 'ruby' }
    stages {
        stage('Example') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
	 stage('build'){
	    steps{
                sh 'ruby --version'
	
    }
}
}
}


