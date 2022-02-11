node{
 
    stage('Clone') {
        git 'https://github.com/bahshoot/app-salaire.git'
    }
    stage('Ansible') {
     ansiblePlaybook (
      become: mouktar
      playbook: 'playbook.yml'
      inventory: 'hosts.yml'
     )
    }
}
