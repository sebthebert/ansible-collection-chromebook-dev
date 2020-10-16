# Ansible Collection for Dev on Chromebook

*Tested on Asus Chromebook C423 / Chrome OS 86*

## Requirements

Update your Chrome OS version.

Activate Linux.

Update your Linux system :

```shell
sudo apt-get update
sudo apt-get upgrade -y
```

Install Ansible :

Ansible version from linux on Chromebook is really old (2.2.1).

Install Python 3 and pip and then install Ansible with pip :
```shell
sudo apt install python3-pip -y

pip3 install ansible==2.9.14
```
