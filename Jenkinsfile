pipeline {
    agent any
    environment{
        path = "${env.WORKSPACE}"
    }
    stages {
        stage('echo') {
            steps {
                echo "Starting pipeline..."
            }
        }
        stage('npm install') {
            steps {
                echo 'npming...'
                npmTool.install(path)
                echo 'npmed...'
            }
        }
    }
}
