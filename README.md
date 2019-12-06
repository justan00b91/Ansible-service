# Creating User using Ansible

* ## Requirements:
Install Ansible in your Linux machine using following commands:
```bash
$ dnf update
$ dnf install ansible
```
* ## Usage:
Run the file using the following command:
```bash
ansible-playbook user.yml
```

* ## Description:
 The following code uses ansible to create new user in the system.
 The code create a user in the base machine hence the hosts is set to localhost.
 Then, the code calls the user module (in-build) to set username and password to the new user account
 The code ends by creating the user in the local system.
