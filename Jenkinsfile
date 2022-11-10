pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''#!/bin/bash
sudo yum -y update
sudo yum -y install httpd
sudo systemctl start httpd
sudo systremctl enable httpd
sudo yum -y install git
git clone https://github.com/anitha8242/ecomm.git /var/www/html'''
      }
    }

  }
}