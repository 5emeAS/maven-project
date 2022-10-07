pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn clean build -Dlicense.skip=true'
        sh 'echo "build"'
      }
    }

    stage('DONE') {
      steps {
        sh 'echo "Done"'
      }
    }

  }
}