pipeline {
    agent {
      node { label 'workstation' }
    }

    stages {

      stage ('Unit-Tests') {
        steps {
          echo 'Unit-Tests'
          // sh 'python -m unittest'
        }
      }

      stage ('Code-Analysis') {
        steps {
          echo 'Code-Analysis'
        }
      }

      stage ('Security Checks') {
        steps {
          echo 'Security Checks'
        }
      }

      stage ('Publish Artifact') {
        steps {
          echo 'Publish Artifact'
        }
      }
    }
}