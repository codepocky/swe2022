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
                echo '2022-06-07-02-39'
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
