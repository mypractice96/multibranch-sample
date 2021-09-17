pipeline {
    agent any
    stages {
        
        stage('dev-deploy') {            
            when {
                branch 'dev'  
            }            
            steps {

                sh 'Deployed to Dev'
                sh 'ls'
                sh 'cat abc.txt'
            }
       }
        
        stage('test-deploy') {            
            when {
                branch 'test'  
            }            
            steps {
                sh 'Deployed to QA'
                sh 'ls'
                sh 'cat abc.txt'
            }
       }  
        
         
        stage('prod-deploy') {            
            when {
                branch 'main'  
            }            
            steps {
                sh 'Deployed to Prod'
                sh 'ls'
                sh 'cat abc.txt'
            }
       }

               
         
     }
}  
