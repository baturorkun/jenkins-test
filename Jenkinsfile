pipeline {
  agent {
    kubernetes {
      yamlFile 'build-pod.yaml'
      defaultContainer 'shell'
    }
  }
       
   
   stages {
        stage('Main') {
            steps {
                sh 'lsb_release -a'
            }
        }
   }
  
}
