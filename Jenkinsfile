pipeline {
  agent any
  stages {
    stage('Run test') {
      parallel {
        stage('Run test') {
          steps {
            bat 'mvn clean test'
          }
        }

        stage('check version') {
          steps {
            bat 'mvn -version'
          }
        }
      }
    }

  }
  tools {
    maven 'MyMaven'
  }
}
