# ssh_automation_asg


README


1)To Give SSH access to New User use following command :

     ansible-playbook -i hosts -e "action=grant" playbooks/ssh-automation.yml
  
2)To Revoke SSH access of a user use following command :  

     ansible-playbook -i hosts -e "action=revoke" playbooks/ssh-automation.yml
     

2)To Remove user use following command :  

     ansible-playbook -i hosts -e "action=remove" playbooks/ssh-automation.yml
