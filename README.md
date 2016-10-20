# installer
The goal of this project is to automate installation of base packages needed on my laptop after a fresh Ubuntu had installed.

###Packages list:
- Git
- Java 8
- Docker
- Docker compose
- Google Chrome
- Virtual Box
- Gnome Shell
- Gnome Tweak tool
- Network manager open connect
- Spotify

### How to run
`ansible-playbook -i inventory.yml playbook.yml --ask-become-pass`