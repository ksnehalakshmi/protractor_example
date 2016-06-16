

node {
   // Mark the code checkout 'stage'....
   stage 'Checkout'

  
//   checkout changelog: false, poll: false, scm: [$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [[$class: 'PerBuildTag']], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '146ff225-d9c5-4466-9ae0-3ff4c646ff30', url: 'https://github.com/ksnehalakshmi/protractor_example.git']]]
checkout changelog: false, poll: false, scm:[$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [[$class: 'PerBuildTag']], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '685b8ba9-1d0c-4c5a-b892-7c920da9cea7', url: 'https://github.com/ksnehalakshmi/protractor_example.git']]]

  
  stage 'Protractor test'
 
  bat "protractor conf.js"

echo "Testing Success"

}
