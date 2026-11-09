pipeline {
    agent any
    stages{
        stage("Checkout"){
            steps{
                echo "Source code checkout completed"
            }
        }
        stage("Info"){
            steps{
                echo "Project: Jenkins CI/CD Demo"
                echo "Pipeline execution started"
            }
        }
        stage("Build"){
            steps{
                echo "Build completed successfully"
            }
        }
        stage("Test"){
            steps{
                echo "Test completed successfully"
            }
        }
        
        stage("Deploy"){
            steps{
                echo "Application deployed successfully"
            }
        }
    }
    post{
        success{
            echo "pipeline completed successfully"
        }
        failure{
            echo "pipeline failed"
        }
    }
}
