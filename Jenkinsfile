pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                script{
                    echo "This is Build"
                }
                // 
            }
        }
        stage('Test') { 
            steps {
                script{
                    sh "This is Build"
                    test "build test"
                }
                // 
            }
        }
        stage('Deploy') { 
            steps {
                script{
                    echo "This is Build"
                }
                // 
            }
        }
    }
     post { 
        always { 
            echo "This sections runs always"
        }
        success{
            echo "This section run when pipeline success"
        }
        failure{
            echo "This section run when pipeline failure"
        }
    }
}