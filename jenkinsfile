pipeline {
    agent { label 'master' }
    stages {
        stage ('echo') {
          steps {
              echo "check the disk space"
          }
        }
        stage ('disk') {
          steps {
              sh 'df -kh'
          }
        }
    }
}
