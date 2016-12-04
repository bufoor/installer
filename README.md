# installer
The goal of this project is to automate installation of base packages needed on my laptop after a fresh Ubuntu had installed.

## requirements
Ansible >=2.1
- `sudo apt-get install software-properties-common`
- `sudo apt-add-repository ppa:ansible/ansible`
- `sudo apt-get update`
- `sudo apt-get install ansible`

##Packages list:
- Git
- Git LFS
- Java 8
- Docker
- Docker compose
- Google Chrome
- Virtual Box
- Gnome Shell
- Gnome Tweak tool
- Network manager open connect
- Spotify
- VLC

## How to run
- `ansible-playbook -i inventory.yml playbook.yml --ask-become-pass`
- `ansible-playbook -i inventory.yml playbook.yml --ask-become-pass --extra-vars "user_email=<<EMAIL>> user_name=<<NAME>>"`
