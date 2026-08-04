# Ansible Automation Demo — Checklist

Purpose: Present a terminal-friendly "slide deck" using Ansible playbooks for demos and workshops.

Prerequisites
- `ansible-core` on the presenter workstation

Quick start
```bash
cd Ansible_Automation_Demo_Using_Ansible_to_Demo
ansible-playbook --syntax-check site-demo.yml
ansible-playbook site-demo.yml
```

Run an individual slide (example):
```bash
ansible-playbook 6_Ansible_Basic_Requirements.yml
```

Verify
- Successful run produces no fatal errors; watch stdout during the demo.

Notes
- This repo is presentation-focused; keep credentials out of files and use vaults if needed.
- See `README.md` for deck flow and recommended presenter environment.
