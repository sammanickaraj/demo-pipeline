info = env.APP_NAME
echo env.APP_NAME
def build_id = ${env.BUILD_ID}
echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
        stage('Configuration Setup') {
            echo "Configuration setup"
            sh "echo ${build_id}"
        }
        stage('Testing Setup') {
            echo "Testing Setup"
        }
        stage('SonarQube scan') {
            echo "SonarQube Scan in progress"
        }
        stage('Copy Image') {
            echo "Copy Image"
        }
         stage('Stage Image') {
            echo "Staging image"
        }