node {
  stage('clone'){
    git 'https://github.com/abdo224/CICD_jenkins.git'

  }
  stage('build'){
    sh label: '', script: 'javac Main.java'
  }
  stage('run'){
    sh label: '', script: 'java Main'
  }


}
