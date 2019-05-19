pipeline {
    agent any

    tools {

        maven 'Maven';
    }
    stages {
        stage ('Compile Stage') {

            steps {
                    echo 'This is a minimal pipeline.' 
                    sh 'mvn -Dmaven.test.failure.ignore=true install' 
                  }
        }

       
    }
}
