pipeline {
  agent any 
  stages {
    stage('Build'){
        steps {
            sh 'echo "Hello World"'
            sh '''
                echo "Multiline shell steps works too"
                ls -lah
            '''
        }
    }
    stage('Testing'){
        steps {
            sh 'tidy -q -e *.html'
        }
    }
  }
}
