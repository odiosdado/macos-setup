# macos setup (minimal setup)

This repo contains configuration to get a macos workstation, up and ready for . It uses the following package and plugin managers:
- ansible
- brew
- oh_my_zsh with antigen

## Pre-reqs
```bash'
- brew https://brew.sh/
- ansible https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html
```

## How to use
1. Clone this repo
2. View the list of packages at `vars/default.yaml`, edit as necessary
    - brew casks and formulas
    - zsh theme (powerlevel10k)
    - oh_my_zsh plugins via antigen
3. Run `ansible-playbook playbook.yaml`
4. If you want to change the default p10k settings
    - Run `p10k configure`
    - Copy `~/p10k.zsh` to `./files/p10k.zsh` for future use 
5. 💎 💰