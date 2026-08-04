# Ansible Automation Demo Using Ansible to Demo

Updated for 2026: RHEL 9/10 guidance, Ansible development workflow, and Ansible Automation Platform 2.7 narrative.

## What This Repo Is

A terminal-friendly "slide deck" implemented as Ansible playbooks.
Each file prints a formatted section and pauses, making it easy to present from SSH sessions, workshops, or screen shares.

## Quick Start

```bash
ansible-playbook site-demo.yml
```

Run a specific slide:

```bash
ansible-playbook 6_Ansible_Basic_Requirements.yml
```

## Deck Flow

1. Cover page
2. Topics
3. What Ansible is
4. Why use Ansible + AAP
5. AAP 2.7 node types
6. Current requirements and tooling
7. Deployment scenarios
8. Simple architecture
9. Simple setup example
10. Enterprise architecture
11. Enterprise setup example
12. Links and next steps

## Recommended Presenter Environment

- RHEL 9 or RHEL 10 workstation/VM
- ansible-core installed
- ansible-lint available for quick quality checks
- terminal font with good Unicode support

## Validation

```bash
ansible-playbook --syntax-check site-demo.yml
```

## Notes

- This repo is for demonstrations and enablement.
- Keep credentials out of these files; use vault-backed variables in real projects.

## License

See LICENSE.
