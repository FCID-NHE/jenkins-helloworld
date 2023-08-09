node {
    
    stage('Clone') {
        git branch: 'main', url: 'https://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@github.com/FCID-NHE/jenkins-helloworld.git'
    }
    stage('Build') {
        sh 'javac Main.java'
    }
    stage('Run') {
        sh 'java Main'
    }
    // some block
}