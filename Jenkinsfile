pipeline{
    agent any
    stages{
        stage("make a directory"){
            steps{
                sh "mkdir ~/jenkins-demo || true"
            }
        }
        stage("add files"){
            steps{
                sh "touch ~/jenkins-demo/file1.txt"
            }
        }
        stage("echo message"){
            steps{
                sh "echo 'Hi I am from Jenkins demo'"
            }
        }
        stage("list files"){
            steps{
                sh "ls -a"
            }
        }
        stage("check current directory"){
            steps{
                sh "pwd"
            }
        }
        stage("make a directory"){
            steps{
                sh "mkdir jenkins-demo/new_folder"
            }
        }
        stage("move file to new directory"){
            steps{
                sh "mv file1.txt jenkins-demo/new_folder"
            }
        }
    }
}