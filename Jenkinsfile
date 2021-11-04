// SHARED_LIBRARY_VERSION = 'v1.0'
// library "shared-library-sam-com@${SHARED_LIBRARY_VERSION}"
// hello( [appName         : "DemoApp",
//         branchName      : "DemoBranch",
//         devApprovers    : "Sam",
//         projectFilePath : "git@github.com:sammanickaraj/shared-library-sam-com.git"] )

// createImage()
node {
        stage('Configuration Setup') {
            echo "Configuration setup"
        }
        stage('Checkout SCM') {
            checkout scm
        }
        stage('SonarQube scan') {
            echo "SonarQube Scan in progress"
            
        }
        stage('Copy Image') {
            echo "Copy Image"
            sh "mkdir /tmp/test_unique"
        }
         stage('Stage Image') {
            echo "Staging image"
        }
}