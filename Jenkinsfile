pipeline {
    agent {
        label 'main'
    }

    triggers {
    githubPush()
    }
    
    stages {
        stage('Sincronización') {
            steps {
                echo '***** Se inicio la sincronización de los repositorios ****'
            }
        }
    }
}
