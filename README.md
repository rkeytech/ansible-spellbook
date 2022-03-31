# Ansible Spellbook
A variety of different Ansible playbooks to automate whatever is possible in your workflow. From server installation and configuration to template instancing and application deployment.

### __But what is Ansible__
Ansible is an IT automation tool. It can configure systems, deploy software, and orchestrate more advanced IT tasks such as continuous deployments or zero downtime rolling updates. Ansible’s main goals are simplicity and ease-of-use. It also has a strong focus on security and reliability, featuring a minimum of moving parts, usage of OpenSSH for transport (with other transports and pull modes as alternatives), and a language that is designed around auditability by humans–even those not familiar with the program.

Ansible manages machines in an agent-less manner. There is never a question of how to upgrade remote daemons or the problem of not being able to manage systems because daemons are uninstalled. Because OpenSSH is one of the most peer-reviewed open source components, security exposure is greatly reduced. Ansible is decentralized–it relies on your existing OS credentials to control access to remote machines. If needed, Ansible can easily connect with Kerberos, LDAP, and other centralized authentication management systems.

### __How to install it on your machine__
You can find many ways to install Ansible on your machine [here](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-the-ansible-community-package) but it can be as easy as a simple sudo apt install ansible. You can read their documentation for a variety of ways to install in different machines and with various utilities.

## Spells
- [x] Install docker/docker SDK on a new server or a group of servers
- [x] Install Portainer for docker to make installation process of containers easier
- [ ] Install NGINX on server(s)
- [x] Install basic applications and configure a newly formated Ubuntu machine
- [ ] Install FoundryVTT Server on Docker
