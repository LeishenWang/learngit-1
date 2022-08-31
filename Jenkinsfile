pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh '''pipeline {
    agent any 
    stages {
        stage(\'Stage 1\') {
            steps {
                echo \'Hello world!\' 
            }
        }
    }
}'''
        }
      }

    }
  }