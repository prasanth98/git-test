pipeline {
    agent any
    stages{
        stage("Start"){
            steps{
                git branch: 'main', credentialsId: '4a9dc4eb-bfa5-4a89-919b-f6ecec9b4261', url: 'https://github.com/prasanth98/git-test.git'
            }
        }
    }
}
