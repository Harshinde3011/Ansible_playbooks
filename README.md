# Ansible_playbooks
playbooks used in real time 

# some adhoc commands
ansible all -m apt -a “upgrade=yes update_cache=yes cache_valid_time=86400” –become 
#
ansible all -m ping 
#
ansible -i inventory all -m “shell” -a “df”
#
ansible -i inventory all -m “shell” -a “nproc”
#
ansible -i inventory all -m “shell” -a “touch test.txt”
