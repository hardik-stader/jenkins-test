pipeline {
  agent any

  stages {
        
    stage('Git') {
      steps {
        echo "Git p0 step"
        // git 'https://github.com/hardik-stader/jenkins-test.git'
      }
    }
     
    stage('Build') {
      steps {
        echo "Build p0 step"
        // sh 'npm install'
        //  sh '<<Build Command>>'
      }
    }  
    
            
    stage('Test') {
      steps {

        echo "Test p0 step"
        // sh 'node test'
      }
    }
  }
}