pipeline {
    agent any

    tools {

        maven 'Maven';
    }
    stages {
        stage ('Compile Stage') {

            steps {
                    echo 'This is a for building the Maven codebase.' 
                    bat 'mvn -Dmaven.test.failure.ignore=true install' 
                  }
              steps {
                    echo 'This is for running Sonar Qube on the code base.' 
                    bat 'mvn sonar:sonar' 
                  }
        }

       
    }
}
