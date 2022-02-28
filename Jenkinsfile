node {
    stage('Clone and Acces') {
        git branch: 'main', credentialsId: 'motdepassegithub', url: 'https://github.com/grethoremas3333/JenkinsFile.git'
     }
    stage('Build') {
        sh label: '', script: 'javac Main.java'
    }
    stage('Run') {
        sh label: '', script: 'java Main'
    }
}
