node {
    stage('clone') {
        git branch: 'main', url: 'https://github.com/Salhianis1/jenkins-Hello-World.git'
        
    }
    
    stage('BUild') {
        sh 'javac Main.java'
        
    }
    
    stage('Run') {
        sh 'java Main'
    }
}
