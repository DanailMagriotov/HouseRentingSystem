pipeline{
    agent any
    stages{
        stage("Install dependencies"){
            steps{
                bat "dotnet restore"
            }
        }
        stage("Build the project"){
            steps{
                bat "dotnet build"
            }
        }
        stage("Run the tests"){
            steps{
                bat "dotnet test"
            }
        }
    }
}