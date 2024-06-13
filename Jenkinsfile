pipeline {
    agent any
    environment{
        MY_USER_PASS = credentials('user-pass')
    }

    stages{
        stage("user password"){
            steps{
    echo "our  user is: $MY_USER_PASS_USR"
    echo "our  user credential is: $MY_USER_PASS_PSW"
  
            }
        }
    }
    
}
