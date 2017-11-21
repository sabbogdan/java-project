<<<<<<< HEAD
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
      always {
        archive '$dist/*.jar'
      }
    }

}

=======
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
      always {
        archive '$dist/*.jar'
      }
    }

}
>>>>>>> bff16119050416bd4031a4315b9c79b5e89ff32b
