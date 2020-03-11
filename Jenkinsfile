pipeline {
   agent any 
   stages {
        stage("Checkout code") {
            steps {
                checkout scm
            }
       }
       stage("Apply Cilium Network Policies to GKE Cluster") {
            steps {
                echo "Cilium Changes started" 
            }
       }
   }
}
