pipeline {
    agent any

    stages {
        stage('Clone'){
            echo "clone git repository"
            sh "mkdir -p build"
            git branch: 'master',
                url: 'https://github.com/maxiestudies/jenkins-sandbox.git'
        }
        stage('Test'){
            when { branch 'master'
            }
            steps{
               sh 'jenkins-sandbox/hello-script.sh'
            }
        }
    }
}
