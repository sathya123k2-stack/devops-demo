pipeline {

    agent any

    stages {

        stage('Clone Repository') {

            steps {

                echo 'Repository downloaded successfully'

                sh 'pwd'

                sh 'ls -la'

            }

        }

        stage('Build') {

            steps {

                echo 'Building application...'

                sh 'date'

            }

        }

        stage('Testing') {

            steps {

                echo 'Testing completed successfully'

            }

        }

    }

}
