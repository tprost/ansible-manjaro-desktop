# Ansible-manjaro-desktop

A playbook for setting up the tools I like on a fresh manjaro
installation.

## Setup

1. Set up SSH

```
sudo pacman -S openssh
sudo systemctl status sshd.service
sudo systemctl enable sshd.service
sudo systemctl start sshd.service
```

2. Set up SSH keys for my Github and Gitlab

```
scp ~/.ssh/id* taylor@<ip>:~/.ssh
chmod 400 ~/.ssh/id_rsa
```

3. Update, upgrade and install Ansible

```
sudo pacman -Syy
sudo pacman -S ansible git --noconfirm
```

## Running

> ./run.sh
