pipeline {
    agent any
    stages{
        stage("Checkout"){
            steps {
                 echo "Checkout Source Code"
            }
        }
        stage("BuildCode"){
            steps {
                 echo "Running Builds"
            }
        }
        stage("CodeAnalysis"){
            steps {
                 echo "Running CodeAnalysis"
            }
        }
        stage("Run Unit Test Cases"){
            steps {
                 echo "Running Unit-Test Cases"
            }
        }
        stage("Push Artifacts"){
            steps {
                 echo "Push Artifacts"
            }
        }

        stage("Deploy to Dev"){
            steps {
                 echo "Running Dev Deployment"
            }
        }
         stage("Run Fuctional Testing"){
            steps {
                 echo "Running Functional Testing"
            }
        }
        stage("Deploy to UAT"){
            steps {
                 echo "Running UAT Deployment"
            }
        }
        stage("Deploy to PRD"){
             input {
                message "Ready to deploy?"
                ok "Yes"
            }
            steps {
                 echo "Running PRD Deployment"
            }
        }


    }
}