pipeline {
    agent any 
    stages {
        stage ('DepoyToDev') {
            steps {
                echo "Deploying to Dev Environment"
            }
        }
        stage ('ProdDeploy') {
            when {
                // brnach condition
                expression { BRANCH_NAME ==~ /(production|staging)/ }
            }
            steps {
                echo "Deploying to production"
            }
        }
    }
}
