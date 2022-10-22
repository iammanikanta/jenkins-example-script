pipeline{
    agent any

    stages{
        stage("say hello"){
            steps{
                sh 'python hello.py'
            }
            post{
                always{
                    echo "========always========"
                }
                success{
                    echo "========A executed successfully========"
                }
                failure{
                    echo "========A execution failed========"
                }
            }
        }
    }
}