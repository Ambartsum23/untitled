pipeline {
  agent any
  stages {
    stage('maven version') {
      parallel {
        stage('maven version') {
          steps {
            bat 'mvn complate test package'
            bat 'mvn --version'
          }
        }

        stage('maven project') {
          steps {
            bat 'mvn complite test package'
          }
        }

      }
    }

  }
}