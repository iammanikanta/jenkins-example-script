pipeline{
    agent any

    stages{
        stage("say hello"){
            steps{
                echo 'welcome divya'
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
