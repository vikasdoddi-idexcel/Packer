node {
         stage('pull code from scm'){
            checkout scm
       }
        stage('packer validate'){
            sh 'packer validate Packer.json'
        }
}
