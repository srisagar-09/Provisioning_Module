pipeline{
    agent any
    environment{
        a = "Devops Engineer"
        b = "Cloud Engineer"
    }
    stages{
        stage('Career options'){
            environment{
                c = "Java Developer"
            }
            steps{
                echo "${a}"
                echo "${b}"
                echo "${c}"
            }
        }
        stage ('Career'){
            steps{
              echo "${a}"
              echo "${b}"  
            }
        }
    }
}
