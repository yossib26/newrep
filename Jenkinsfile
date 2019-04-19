pipeline{
    agent any
    stages {
        
        stage('foo') {
            
            parallel {
            
                stage('first') {
                    steps {
                        echo 'first ..........'
                        sleep 8
                    }
                }
                
                stage('second') {
                    steps {
                        echo 'second ..........'
                        sleep 8
                    }
                }
                
            }
        }       
    }
}
