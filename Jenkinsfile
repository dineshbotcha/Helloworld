pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}

pipeline {
    agent { docker 'ruby' }
    stages {
        stage('build') {
            steps {
                sh 'ruby --version'
            }
        }
    }
}
