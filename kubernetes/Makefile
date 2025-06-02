ping:
	ansible -m ping all -i inventory/hosts.ini
check:
	ansible-playbook -i inventory/hosts.ini playbooks/cluster.yaml --check
run:
	ansible-playbook -i inventory/hosts.ini playbooks/cluster.yaml
node:
	ansible-playbook -i inventory/hosts.ini playbooks/cluster.yaml -l ${NODE} -vv
