pipeline {

    agent { node { label 'workstation' } }

    environment {
      SSH = credentials('SSH')
      DEMO_URL = "google.com"
    }

    options {
      ansiColor('xterm')
    }


    stages {
        stage('Hello-2') {
            steps {
                echo 'Hello World'
                sh 'env'
            }
        }
    }

    post {
      always {
        sh 'echo post'
      }
    }

}
