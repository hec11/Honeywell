pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        mail(subject: 'Test', body: 'we got it?', from: 'asdf@asdf.com', to: 'chuan.he@componentcontrol.com')
      }
    }
  }
}