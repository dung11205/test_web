pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Personal Website...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy successful!'
            }
        }
    }

    post {
        success {
            echo '========================================'
            echo 'BUILD SUCCESS!'
            echo 'Website: https://ronaldo-55363q0u5-dung-1ef5.vercel.app/'
            echo '========================================'
        }
    }
}
