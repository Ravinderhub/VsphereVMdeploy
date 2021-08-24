pipeline {
  agent any
  stages {
    stage('Log Tool Versions /Shell Script') {
      parallel {
        stage('Log Tool Versions /Shell Script') {
          steps {
            sh '''mvn --version
git --version
java -version
'''
          }
        }

        stage('Check for POM') {
          steps {
            fileExists 'pom.xml'
          }
        }

      }
    }

  }
}