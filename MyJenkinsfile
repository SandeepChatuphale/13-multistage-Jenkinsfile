pipeline {
    agent any
    
    stages 
    {
        stage('Check out')
        {
            steps{
                echo "Checkout"
            }
        }
        
        
        stage('Build') 
        {
            steps 
            {
              echo "Build"
            }
        }
        
        stage('Test') 
        {
            steps 
            {
              echo "Test"
            }
        }
        
        stage('Approve Deploy') 
        {
            steps 
            {
              input "Approve Deployment?"
            }
        }
        
        stage('Deploy') 
        {
            steps 
            {
              echo "Deploy"
            }
        }
    }
}
