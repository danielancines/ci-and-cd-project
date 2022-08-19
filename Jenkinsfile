pipeline {
    agent any
    stages {
          stage('Get Code (main)') {
              when {
                  branch 'main'
              }
              steps {
                script {
                  echo 'main'
                }
              }
          }
          stage('Get Code (staging)') {
              when {
                  branch 'staging'
              }
              steps {
                script {
                  echo 'staging'
                }
              }
          }
        stage('Get Code (develop)') {
              when {
                  branch 'develop'
              }
              steps {
                script {
                  echo 'develop'
                }
              }
          }
    }
}
