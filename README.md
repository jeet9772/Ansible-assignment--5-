# Ansible Assignment 5

## Ansible Role

### Objective

Create an Ansible role for the assigned tool with the following features:

* Install a specific version of the tool
* Support different operating systems
* Keep configuration values variableized
* Use Jinja2 templates
* Manage configuration files using templates
* Use handlers separately from tasks
* Allow the role to run on CentOS, Ubuntu, or both

---

# Role Structure

```text
assignment-5/
│
├── inventory
├── playbook.yml
│
└── roles/
    └── tool_role/
        ├── tasks/
        │   └── main.yml
        ├── handlers/
        │   └── main.yml
        ├── templates/
        │   └── tool.conf.j2
        ├── defaults/
        │   └── main.yml
        └── vars/
            └── main.yml
```

---

# Ubuntu Installation

The Redis Ansible role was executed successfully on the Ubuntu operating system.

### Ubuntu Installation Screenshot

![Ubuntu Redis Installation](screenshots/ubuntu-installation.png)

---

# RedHat Installation

The Redis Ansible role was also executed successfully on the RedHat operating system.

### RedHat Installation Screenshot

<img width="1440" height="900" alt="Screenshot 2026-09-01 at 2 16 17 PM" src="https://github.com/user-attachments/assets/5cbe0eb1-589d-4b7b-ada5-be48c4838712" />




