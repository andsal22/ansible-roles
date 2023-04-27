# ansible-roles


# Requirements


- A computer
- Ansible installed
- Python3 installed
- A Windows Server that you want to manage
- A Zabbix server that will manage it



# How to run the Ansible Playbook


Once you downloaded all the files, you have to modify the variables on the files named "main.yaml" under all the "vars" subfolders, that are located inside the "agent" and "zabbix_host" folder, depending on your needs. After that, modify the "hosts" file, and put the ip addresses that correspond to your Windows Server and your Ansible.

To run the playbook, just open a linux terminal, navigate to the "ansible-roles" folder and run ```ansible-playbook -i hosts playbook.yaml```
