pipeline {
    agent any
    environment {
        PROJECT_NAME = "Project-red"
    }
    stages{
        stage("Build"){
            steps{
                echo "Building an application ${PROJECT_NAME}"
            }
        }
        stage("Test") {
            steps {
                when {
                    expression {
                        BRANCH_NAME = "main"
                    }
                }
                echo "Testing application ${PROJECT_NAME}"
            }
        }
    }
}
