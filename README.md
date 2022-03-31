# pizeros

ansible -k all -i inventory -m shell -a ip addr show dev wlan0

ANSIBLE_VERBOSITY=1 ansible-playbook -k -i inventory main.yml

ansible all -i inventory -m shell -a "sleep 1s; shutdown now" -b -B 60 -P 0

# to pass key passphrase

ssh-agent

ssh-add