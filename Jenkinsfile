pipeline {
  agent any
  stages {
    stage('build') {
      steps {
          sh "printenv | sort"
          sh 'bash $WORKSPACE/build/build.sh'
      }
    }

  }
}
