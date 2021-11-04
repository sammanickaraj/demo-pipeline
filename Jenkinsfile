library identifier: 'shared-library-sam-com@v1.o',
    // 'mylibraryname' is just an identifier, it can be anything you like
    // 'master' refers to a valid git ref (branch)
    retriever: modernSCM([
      $class: 'GitSCMSource',
//       credentialsId: 'your-credentials-id', // remove this if it's public!
      remote: 'https://github.com/sammanickaraj/shared-library-sam-com.git'
])
hello( [appName         : "DemoApp",
        branchName      : "DemoBranch",
        devApprovers    : "Sam",
        projectFilePath : "git@github.com:sammanickaraj/shared-library-sam-com.git"] )