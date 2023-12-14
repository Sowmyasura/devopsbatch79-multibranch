pipeline {   
    agent any

    stages {   
        stage('Master upbrdate anch') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('sprint1new update') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
