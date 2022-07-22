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
        }
        stage('test'){
            steps {
                script{
                    gv.testGroovy();
                    }
                
            }
        }
    }
}

