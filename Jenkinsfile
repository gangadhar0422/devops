pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
       post{
        always{
            emailext body: 'pipeline', subject: 'pipeline status', to: 'gangadharm1592@gmail.com'
    }
  }
  }
}
