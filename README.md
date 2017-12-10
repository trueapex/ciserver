# Continuous Integration Server
A Continuous Integration and Continuous Delivery Server using Jenkins

## Technology Stack
Ubuntu Server (Xenial)\
Ansible\
Jenkins

## Installation
Follow the commands below for installing Jenkins.

#### Install Ansible
```
$ sudo apt-get update
$ sudo apt-get install software-properties-common
$ sudo apt-add-repository ppa:ansible/ansible
$ sudo apt-get update
$ sudo apt-get install ansible
```

#### Install Jenkins
```
$ wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -
$ sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
$ sudo apt-get update
$ sudo apt-get install jenkins
```

## Sponsors
[True Apex](https://www.trueapex.com) - Web Design and Development

## Maintainers
[Romualdo Dasig](https://github.com/dasigr)

## License
GNU General Public License v3