pipeline {

    agent any

    stages {

        stage("Build") {

            steps {

                script {
                    sh "echo 'Buiding' "
                }
            }
        }

        stage("Test") {

            steps {

                script {
                    sh "echo 'Testing' "
                }
            }
        }

        stages("Deploy") {

            steps {

                script {
                    sh "echo 'Deploying' "
                }
            }
        }
    }
}
