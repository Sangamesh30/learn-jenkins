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
      alwsys{
        sh 'echo post'
         }
    }
}
