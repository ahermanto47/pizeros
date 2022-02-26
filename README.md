# pizeros

ansible -k all -i inventory -m shell -a ip addr show dev wlan0
ANSIBLE_VERBOSITY=1 ansible-playbook -k -i inventory main.yml
