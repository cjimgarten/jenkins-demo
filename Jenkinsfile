pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        
        // random stuff
        echo 'Stage 1'
        sh 'pwd'
        sh 'ls -la'
      }
    }
    stage('Stage 2') {
      steps {
        
        // java info
        sh 'java -version'
        
        // python3 info
        sh 'python3 -V' 
      }
    }
  }
}
