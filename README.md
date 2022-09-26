Requirements
------------

- Ansible version 2.9 or higher

How to use
----------------

Edit `hosts` file according to your preference.

Next, test the playbook using the following example:

    ansible-playbook site.yml -i hosts -e ansible_python_interpreter=/usr/bin/python3 --check

To deploy it, use:

    ansible-playbook site.yml -i hosts -e ansible_python_interpreter=/usr/bin/python3