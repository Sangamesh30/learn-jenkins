pipeline {

    agent { node { label 'workstation' } }

    stages {
        stage('Hello-2') {
            steps {
                echo 'Hello World'
            }
        }
    }

    post{
      always{
        sh 'echo post'
         }
    }
}
