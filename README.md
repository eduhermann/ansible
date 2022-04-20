# ansible

Repository where the main goal is share some playbooks to optimize our time in repetitive tasks related to sysadmin.

Each project has a description about "What does this project do?"

### Requirements

- You need create a directory on your home directory called "git":
```bash
mkdir ~/git

cd ~/git
```

- Clone this project:
```bash
git clone git@github.com:eduhermann/ansible.git

```

- IMPORTANT: always update your inventory file according to your environment.

- To run some playbook, you need to enter the directory, and then run the Ansible playbook using below command:
```bash
cd ~/git/ansible/project01-sshKey

ansible-playbook project01-sshKey/playbook/playbook.yml
```

Now, you can test all of projects contained here.

### Ansible projects available in this repository

- [x] Project 01 - Import SSH Pub key (Ubuntu/Debian, RedHat)
- [x] Project 02 - Update operating system (Ubuntu/Debian, RedHat)
- [x] Project 03 - Customize O.S. and install pkts (Ubuntu/Debian, RedHat)