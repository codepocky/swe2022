pipeline {
    agent {
        label "demoAgent" //node's label
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'practice pipeline'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
    post {
        always {
            echo 'pipeline job done!!!'
        }
    }
}
