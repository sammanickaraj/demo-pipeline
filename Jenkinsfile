def random_var = 'Hi Sam'
def testing_var = "Testing setup"
def env_testvar = env.BUILD_ID

        stage('Configuration Setup') {
            echo "Configuration setup"
            echo "${random_var}"
        }
        stage('Testing Setup') {
            echo "${testing_var}"
        }
        stage('SonarQube scan') {
            echo "SonarQube Scan in progress"
            echo "${env_testvar}"
        }
        stage('Copy Image') {
            echo "Copy Image"
        }
         stage('Stage Image') {
            echo "Staging image"
        }