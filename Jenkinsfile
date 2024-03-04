pipeline {
  agent any
  triggers{
    pollSCM('H/2 * * * *')
  }
  stages {
    stage("Configuration setup...") { 
            steps {
                echo "Configuration setup..."
            }            
    }
  }
}