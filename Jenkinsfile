@Library('shared-library') _

pipeline{
    agent any

    stages{
        
        stage('Git SCM'){
            
            steps{
            gitCheckout{
                branch: "main",
                url: "https://github.com/Skywalker4123/shared-library.git"
            }    
            } 
        }
    }
}
