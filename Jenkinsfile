node {
         stage('pull code from scm'){
            checkout scm
       }
        stage('packer validate'){
            sh 'packer validate Packer.json'
        }
        stage('packer inspect'){
            sh 'packer inspect Packer.json'
        }
        stage('packer build'){
            sh 'packer build Packer.json'
        }
}
