info = env.APP_NAME
echo env.APP_NAME
echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
pipeline {
    agent any
    stages {
        stage('Example Build') {
            steps {
                sh 'mvn -B clean verify'
            }
        }
    }
}