pipeline {
    agent any
    stages {
        stage('Build develop') {
            when {
                branch 'develop'
            }
            steps {
                echo 'develop'
            }
        }
        stage('build master') {
            when {
                branch 'master'
                 
            }
            steps {
                echo 'master'
            }
        }
    }
}
