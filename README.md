# Description
Collection of ansible scripts creating local k8s cluster on server with KVM-based virtualization

# How to run?
Run with:
```
ansible-playbook playbooks/*.yaml --extra-vars "ansible_user=<USERNAME>" --extra-vars "ansible_sudo_pass=<PASWORD>"
```

