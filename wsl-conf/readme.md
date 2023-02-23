# wsl-conf


This is a simple ansible playbook, that is used for setup .bashrc for new users by `adduser`

Verified on:
* Ubuntu-22.04
* kali-linux

### Pre-requirements

[Ansible](#install-ansible) must be installed.

### Usage

1. `cd` into project directory.
2. Execute:

    ```bash
    ansible-playbook wsl_conf.yml --extra-vars "lines_count=?"
    ```
    * `?` - it can be value **equal with 2** or **not equal with 2** 

### Install Ansible

* Update repos list:

    ```bash
    sudo apt-get update
    ```

* Install Ansible:

    ```bash
    sudo apt-get install ansible -y
    ```
    * `-y` - assume "yes" as answer to all prompts and run non-interactively


---
