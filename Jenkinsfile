pipeline {
    agent any


    stages {
        stage('SCM Checkout'){
          git 'https://github.com/apraka/upstream'
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
}
