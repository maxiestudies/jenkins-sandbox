pipeline {
    agent any

    stages {
        stage('Test'){
            when { branch 'master'
            }
            steps{
               sh 'hello-script.sh'
            }
        }
    }
}
