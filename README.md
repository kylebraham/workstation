# Ansible playbooks for workstation setup. 

## Requirements:

```bash
 dnf install ansible-playbook
 ansible-galaxy collection install community.general
```

## Installation:

**<span style="color:red">Order is important; need to install core first</span>.** 


Install core playbook:
```bash
 ansible-playbook -K ansible/Fedora/core.yml
```

Install nvidia playbook:
```bash
 ansible-playbook -K ansible/Fedora/nvidia.yml
```

Install gaming playbook:
```bash
 ansible-playbook -K ansible/Fedora/gaming.yml
```

reboot machine:
``` bash
reboot
```
