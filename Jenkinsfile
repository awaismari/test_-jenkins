pipeline {
    agent any
    stages {
        stage("build") {
            steps {
                echo 'building the app'
            }
        }
         stage("test") {
            steps {
                echo "testing the app ${env.BRANCH_NAME}"
            }
        }
         stage("deploy") {
            steps {
                echo 'deploying the app'
            }
        }
    }
    post {
        always {
            echo 'From post Obj'
        }
    }
}