pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'Start Build'
      }
    }
    stage('Boot ') {
      parallel {
        stage('Boot ') {
          steps {
            bat 'echo "Boot"'
          }
        }
        stage('Operational') {
          steps {
            bat 'echo "Operational"'
          }
        }
        stage('PDI') {
          steps {
            bat 'echo "PDI"'
          }
        }
      }
    }
    stage('Script Test') {
      steps {
        bat 'echo "test Script"'
      }
    }
  }
}
