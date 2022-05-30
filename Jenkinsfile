pipeline {
  agent any

  stages {
    stage('Deploying App to Kubernetes') {
      steps {
        script {
          kubernetesDeploy(configs: "sample-app-definition.yaml", kubeconfigId: "kubernetes")
        }
      }
    }

  }

}
