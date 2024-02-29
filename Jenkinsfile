pipeline {
    agent any
    stages {
        stage("List Directories"){
            steps{
                sh "ls"
            }
        }
        stage("Folder Location"){
            steps{
                sh "pwd"            
            }
        }
        stage("Echo Job"){
            steps{
                sh "run.sh"            
            }
        }
        
    }



}
