pipeline {
    agent any
    stages{
        stage ('clone'){
        steps{
            checkout scm 
        }
    }
    stage ('bulid'){
        steps{

        sh "https://github.com/alshamari/AWS/tree/master/application/api.py" 
            
        }
    }
    
}
}
