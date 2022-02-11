node{
 
    stage('Clone') {
        git 'https://github.com/bahshoot/app-salaire.git'
    }
    stage('Ansible') {
     ansiblePlaybook (
      colorized: true, 
      playbook: 'playbook.yml'
      inventory: 'hosts.yml'
     )
    }
}
