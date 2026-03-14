# Ansible Role: MySQL Server

Automates the installation and configuration of MySQL database servers.

---

## 📌 Overview

The **mysql_server** role installs and configures a MySQL database service for application environments.

It enables automated database server provisioning within infrastructure environments.

---

## 🚀 Features

* MySQL installation
* Database service configuration
* Infrastructure automation ready

---

## 🧰 Requirements

* Ansible >= 2.9
* Linux server

---

## ⚙️ Role Variables

Example variables:

```yaml
mysql_root_password: root
mysql_port: 3306
```

---

## ▶️ Example Playbook

```yaml
- hosts: db_servers
  become: true
  roles:
    - gustavoohrodrigues.mysql_server
```

---

## 📦 Installation

```bash
ansible-galaxy install gustavoohrodrigues.mysql_server
```

---

## Author

**Gustavo Henrique Rodrigues**
SysAdmin

LinkedIn
https://www.linkedin.com/in/gustavo-henrique-rodrigues-3070a5260

---

## 📜 License

MIT
