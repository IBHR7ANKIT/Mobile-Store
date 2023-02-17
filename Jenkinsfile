pipeline{
    agent any
    stages{ 
        stage ('checkout the code from SCM'){
 steps{ 
    echo 'checkout the code'
 }
        }

        stage('build the project'){
            stages{
                echo 'cheakout the code'
            }
        }
        stage ('Build the project'){
            steps{
                echo 'building the project'
                sh 'mvn clean install -DskipTests'
            }
        }
    }
}