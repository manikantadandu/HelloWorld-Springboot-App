pipeline{
    agent any
        stages{
            stage('Git clone'){
                steps{
                    git 'https://github.com/manikantadandu/HelloWorld-Springboot-App.git'
                }
            }
            stage('Test'){
                steps{
                   echo"Testing completed"
                }
            }
            stage('Build'){
                steps{
                   echo"Build completed"
                }
            }
        }
        
    }
    
    
