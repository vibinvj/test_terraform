pipeline{
    agent{
        label "node"
    }
    stages{
        stage("sonar code quality check"){
            agent{
                docker{
                    image openjdk:11
                }
            }
            steps{
                script{
                    withSonarQubeEnv(credentialsId: 'sonar-token') {

                    }

                }

            }
        }
    }
}