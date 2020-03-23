node {
    stage('Clone') { 
        git 'https://github.com/priximmo/jenkins-helloworld'
    }
    stage('Build') { 
        sh label: '', script: 'javac Main.java'
    }
    stage('Run') { 
        sh label: '', script: 'java Main'
    }
}

