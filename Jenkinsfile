def gv
pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                script{
                    gv.buildGroovy();
                    }
                
            }
             steps {
                script{
                    gv.testGroovy();
                    }
                
            }
        }
    }
}
