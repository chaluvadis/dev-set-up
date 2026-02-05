# Ubuntu Dev Setup Playbook for 2015 iMac

This Ansible playbook automates the setup of a **full development environment** on Ubuntu for a 2015 iMac. It installs your preferred development tools, system utilities, Node.js stack, Docker, Kubernetes tools, and configures **Oh My Zsh**.

---

## Features

- **System utilities**: `htop`, `tmux`, `tree`, `bat`, `fd`, `ripgrep`, `fzf`, `neofetch`  
- **Shell**: `zsh` with Oh My Zsh and recommended plugins (`git`, `docker`, `zsh-autosuggestions`, `zsh-syntax-highlighting`)  
- **Git** + GitHub CLI  
- **VS Code Insiders**  
- **Node.js stack**: Node.js 24, `pnpm`, TypeScript, BiomeJS, ApiDog CLI  
- **Docker** + Docker Desktop  
- **Kubernetes tools**: `kubectl`, `Helm`, `Minikube`, `kubectx`/`kubens`

---

## Prerequisites

- Ubuntu 22.04+ (or latest LTS recommended)  
- Sudo privileges  
- Internet connection  
- Python 3 installed (default on Ubuntu)  
- Ansible installed (see below)

### Install Ansible

```bash
sudo apt update
sudo apt install -y ansible
ansible --version
