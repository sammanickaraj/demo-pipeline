// SHARED_LIBRARY_VERSION = 'v1.0'
// library "shared-library-sam-com@${SHARED_LIBRARY_VERSION}"
// hello( [appName         : "DemoApp",
//         branchName      : "DemoBranch",
//         devApprovers    : "Sam",
//         projectFilePath : "git@github.com:sammanickaraj/shared-library-sam-com.git"] )

// createImage()


library identifier: 'shared-library-sam-com@dev',
    // 'mylibraryname' is just an identifier, it can be anything you like
    // 'master' refers to a valid git ref (branch)
    retriever: modernSCM([
      $class: 'GitSCMSource',
//       credentialsId: 'your-credentials-id', // remove this if it's public!
      remote: 'https://github.com/sammanickaraj/shared-library-sam-com.git'
])

node {
        stage('Configuration Setup') {
            echo "Configuration setup"
        }
        stage('Checkout SCM') {
            checkout scm
        }
        stage('Openshift Login') {
            sh "oc login -u kubeadmin -p HqC3I-wgtiB-q7qCf-KEsuK https://api.crc.testing:6443 --insecure-skip-tls-verify"
            }
        stage('Switch Project') {
            sh "oc project mysql-project"
        }
         stage('Stage Image') {
            echo "Staging image"
        }
}