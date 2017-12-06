pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
           
            parallel A: {
                steps {
                    echo 'Testing A..'
                }
            },
            B: {
            
            steps {
                    echo 'Testing B..'
                }
            
            
            }
            
        } 
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
