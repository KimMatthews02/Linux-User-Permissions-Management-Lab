# Linux User & Permissions Management Lab

## Overview

This project simulates a real-world Linux system administration environment focused on user management, group-based access control, and file permission security.

It demonstrates practical skills used in SOC operations, Linux system administration, and RHCSA-level environments.

---

## Objectives

- Create and manage Linux users and groups
- Configure secure shared directories
- Implement setgid for group inheritance
- Apply least privilege access principles
- Configure sudo access for administrative users
- Validate and troubleshoot permission issues

---

## Lab Architecture

A development team called **engineering** is configured with controlled access to a shared directory:

- Users: `eng1`, `eng2`, `lead`
- Group: `engineering`
- Shared directory: `/srv/engineering`

---

## Project Structure

linux-user-permissions-lab/
│
├── README.md
├── scripts/
│ ├── setup_users.sh
│ ├── setup_groups.sh
│ ├── configure_permissions.sh
│ ├── sudo_config.sh
│
├── screenshots/
│ ├── users_created.png
│ ├── group_setup.png
│ ├── permissions_validation.png
│ ├── setgid_test.png
│ ├── sudo_test.png
│
├── logs/
│ ├── audit.log
│
└── docs/
├── troubleshooting.md

