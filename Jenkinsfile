pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        
        // random stuff
        echo 'Stage 1'
        sh 'ls -la'
        
        // java info
        echo $JAVA_HOME
        sh 'java -version'
      }
    }
  }
}
