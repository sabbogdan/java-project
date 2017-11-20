pipeline {
  agent any

    stages {
      stage('build') {
        steps {
         sh 'ant -f build.xml -v'
        }
      }
    }
    post {
      allways {
        archive '$dist/*.jar'
      }
    }
}
