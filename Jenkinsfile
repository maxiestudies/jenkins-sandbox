pipeline {
    agent any

    stages {
        stage('Test'){
            when { branch 'master'
            }
            steps{
               sh 'jenkins-sandbox/hello-script.sh'
            }
        }
    }
}
