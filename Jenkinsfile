node {
   
    stage('git') {
        git 'https://github.com/devopswithdayanand/gmail.git'
    }
    
    stage('build') {
        sh 'mvn clean package'
    }
}
