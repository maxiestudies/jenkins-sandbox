pipeline {
    agent any

    stages {
        stage('Test'){
            when {
                expression {
                    env.BRANCH == 'master'
                }
            }
            steps{
               sh 'echo hello'
            }
        }
    }
}
