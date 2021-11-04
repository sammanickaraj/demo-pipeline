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
        stage('Openshift Login') {
            sh 'oc login -u kubeadmin -p HqC3I-wgtiB-q7qCf-KEsuK https://api.crc.testing:6443'
            set +e
        }
        stage('Copy Image') {
            echo "Copy Image"
        }
         stage('Stage Image') {
            echo "Staging image"
        }
}