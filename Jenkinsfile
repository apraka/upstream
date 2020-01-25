pipeline {
    agent any


    stages {
        stage('SCM Checkout'){
            steps{  
              git 'https://github.com/apraka/upstream'
             }
        }  
        stage ('Compile Stage') {
          steps {
                echo 'Compile stage'
                }
            }
        stage ('Testing Stage') {
          steps {
                echo 'testing'
            }
       } 
    }    
      post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
