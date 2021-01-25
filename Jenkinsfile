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
                echo path
                // script{                    
                //     npmTool.install(path)
                //     echo 'npmed...'
                // }
            }
        }
    }
}
