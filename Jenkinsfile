pipeline {
  agent any
  stages {
    stage('Install Something') {
      steps {
        sh '''sudo yum install httpd -y
sudo systemctl start httpd
'''
      }
    }

  }
}