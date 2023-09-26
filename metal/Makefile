.POSIX:

pxe:
	ANSIBLE_HOST_KEY_CHECKING=False ansible-playbook --inventory=inventory.ini playbook.yaml --tags pxe

console:
	ANSIBLE_HOST_KEY_CHECKING=False ansible-console --inventory=inventory.ini --user ubuntu --private-key ~/.ssh/id_rsa
