# Ansible-manjaro-desktop

A playbook for setting up the tools I like on a fresh manjaro
installation.

## Setup

1. Update, upgrade and install Ansible

```
sudo pacman -Syy
sudo pacman -S ansible git --noconfirm
```

2. Set up SSH keys for my Github and Gitlab

```
...
chmod 400 ~/.ssh/id_rsa
```

## Running

> ./run.sh
