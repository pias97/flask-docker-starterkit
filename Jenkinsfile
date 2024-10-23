pipeline {

    agent { label "jenkins-w1"}

    stages {
        stage(Code){
            steps{
                echo "Cloning the code"
            }
        }

        stage(Build){
            steps{
                echo "Building the code"
            }
        }

        stage(Test){
            steps{
                echo "Testing the code"
            }
        }

        stage(Deploy){
            steps{
                echo "Deploying the Application"
            }
        }
    }


}
