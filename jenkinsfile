pipeline {
    agent 
    {
        label 'SmartEstimator_Node'
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World from groovy script'
            }
        }
        stage('second')
        {
            steps{
                echo 'This is second stage going on'
            }
        }
        
    }
    post
    {
        always
        {
            echo 'Always block executing'
        }
        success
        {
         echo 'Success block executing'
        }
        failure
        {
            echo 'Failure block executing'
        }
    }
    
}
