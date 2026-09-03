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

<img width="1440" height="900" alt="Screenshot 2026-09-03 at 1 51 26 PM" src="https://github.com/user-attachments/assets/cf785daf-4387-475f-afc9-8534724b70df" />



---

# RedHat Installation

The Redis Ansible role was also executed successfully on the RedHat operating system.

### RedHat Installation Screenshot

<img width="1440" height="900" alt="Screenshot 2026-09-03 at 1 49 39 PM" src="https://github.com/user-attachments/assets/5787cbf8-d8ad-4c2f-adad-abb2ab38b3ce" />





