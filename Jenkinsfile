pipeline {

    agent { node { label 'workstation' } }

environment {
   SSH = credentials('SSH')

}
    stages {
        stage('Hello-2') {
            steps {
                echo 'Hello World'
                sh 'env'
            }
        }
    }

    post{
      always{
        sh 'echo post'
         }
    }
}
