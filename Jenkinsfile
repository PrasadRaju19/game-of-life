node {
    stage ('SCM') {
        git 'https://github.com/PrasadRaju19/game-of-life.git'
    }
    
    stage('Build & Package') {
        sh 'mvn package'
    }

}