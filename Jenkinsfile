node {
    stage('clone') {
        git 'git branch: 'main', url: 'http://github.com/Salhianis1/jenkins-Hello-World.git''
        
    }
    
    stage('BUild') {
        sh 'javac Main.java'
        
    }
    
    stage('Run') {
        sh 'java Main'
    }
}
