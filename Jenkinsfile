pipeline {
  agent any
  stages {
    stage('1') {
      steps {
        echo 'its 1 step'
        sh 'ls -l '
      }
    }

    stage('2') {
      steps {
        sleep 2
        sh 'echo "step 2"'
      }
    }

  }
  environment {
    test_env = '"test"'
  }
}