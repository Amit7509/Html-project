pipeline {
  agent any
  stages {
    stage('Install Something') {
      steps {
        sh '''sudo yum install httpd -y

'''
        sh 'sudo systemctl start httpd'
      }
    }

    stage('Deployment') {
      steps {
        sh 'sudo cp * /var/www/html/'
      }
    }

  }
}