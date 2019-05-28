pipeline { 
    agent any  
    stages { 
        stage('clean') { 
            steps { 
              sh 'mvn -Dmaven.test.failure.ignore=true clean'
            }
        }
        
         stage('install') { 
            steps { 
              sh 'mvn -Dmaven.test.failure.ignore=true install'
            }
        }
    }
}
