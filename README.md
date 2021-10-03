# Description
Collection of ansible scripts creating local k8s cluster on server with KVM-based virtualization

# How to run?

1. Install requirements:
```shell
ansible-galaxy install -r requirements.yaml
```
2. Create cluster with following command:
```shell
ansible-playbook playbooks/{10,20,30}-*.yaml --extra-vars "ansible_user=<USERNAME>" --extra-vars "ansible_sudo_pass=<PASWORD>"
```
3. Play & enjoy =)
4. Remove cluster:
```shell
ansible-playbook playbooks/90-*.yaml --extra-vars "ansible_user=<USERNAME>" --extra-vars "ansible_sudo_pass=<PASWORD>"
```
