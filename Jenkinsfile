pipeline {
  agent any
  stages {
    stage('maven project') {
      parallel {
        stage('maven project') {
          steps {
            bat 'mvn -version'
          }
        }

        stage('') {
          steps {
            bat 'mvn compile test package'
          }
        }

      }
    }

  }
}