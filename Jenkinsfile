pipeline {
    agent { 
        node {
            label 'docker_agent_python'
            }
      }
    triggers {
        pollSCM ' * * * * * '
    }
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh '''
                echo "doing Building stuff.."

                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
               echo "doing Testing stuff.."
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "doing delivery stuff.."
                '''
            }
        }
    }
}
