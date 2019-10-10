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
        stages {
          stage('Boot ') {
            steps {
              bat 'echo "Boot"'
            }
          }
          stage('Boot Build') {
            steps {
              bat 'echo "Boot Build"'
            }
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
