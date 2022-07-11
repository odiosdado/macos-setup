# macos setup (minimal setup)

This repo contains configuration to get a macos workstation, configured and ready for work

## Pre-reqs
```bash'
- brew https://brew.sh/
- ansible https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html
```

## How to use
1. Clone this repo
2. View the list of packages at `vars/default.yaml`, edit as necessary
3. Run `ansible-playbook playbook.yaml`
4. Run `p10k configure` to customize zsh
5. 💎 💰