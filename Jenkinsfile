pipeline {
    agent any

    stages {
        stage('Test'){
            when {
                env.BRANCH == 'master'
            }
            steps{
               sh 'echo hello'
            }
        }
    }
}
