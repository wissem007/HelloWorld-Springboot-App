pipeline{
    agent any
    stages{
        stage('Git clone'){
            steps{
                git 'https://github.com/wissem007/HelloWorld-Springboot-App.git'
            }
        }
        
        stage('maven build'){
            steps{
                sh 'mvn package'
            }
        }
        
    }
}
