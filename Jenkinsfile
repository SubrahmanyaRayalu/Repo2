pipeline {
    agent any

    tools {

        maven 'Maven';
    }
    stages {
        stage ('Compile Stage') {

            steps {
                    echo 'This is a minimal pipeline.' 
                    bat 'mvn -Dmaven.test.failure.ignore=true install' 
                  }
        }

       
    }
}
