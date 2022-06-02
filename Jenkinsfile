import java.text.SimpleDateFormat
pipeline {
    agent any
    
    stages {
        stage('Prepare Today Date') {
            steps {
                 script {
                    def dateFormat = new SimpleDateFormat("yyyyMMdd")
                    def date = new Date()
                
                    today = dateFormat.format(date)                
                    
                }                
            } 
        }
        stage('Print Today Date') {
            steps {
                  echo today
            } 
        }
}
}
