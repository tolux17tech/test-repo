pipeline{
    agent any
    tools{
        maven "maven"
    }
    stages{
        stage("Git Clone"){
            steps{
                script{
                    sh "echo hello"
                }
            }
        }
        stage("Maven build"){
            steps{
                script{
                    sh "echo hello"
                }
            }
        }
        stage("Sonaqube test"){
            steps{
                script {
                    sh "echo hello"
                }
            }
        }
        stage("test_build"){
            agent any
            steps{
                script{
                    sh "echo hello"
                }
            }
        }

    }
    post{
            always{
                sh "echo job well done"
            }
             failure{
                sh "echo job well done"
            }
        }
}
