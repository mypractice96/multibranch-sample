pipeline {
    agent any
    stages {
        
        stage('dev-deploy') {            
            when {
                branch 'dev'  
            }            
            steps {
                sh 'ls'
                sh 'cat abc.txt'
            }
       }
        
        stage('test-deploy') {            
            when {
                branch 'test'  
            }            
            steps {
                sh 'ls'
                sh 'cat abc.txt'
            }
       }     
         
     }
}  
