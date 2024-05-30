# setup-macosx

Setup dev tools to have python3 (try to run python3 in a terminal).

Test connection:

```sh
ansible -i inventory.yml macos_host -m ping
```

Install dependencies:

```sh
ansible-galaxy install -r requirements.yml
```

Run one of the available playbooks:

```sh
ansible-playbook -i inventory.yml -K playbook.yml
```

## Credits

* https://github.com/geerlingguy/ansible-collection-mac
* https://github.com/geerlingguy/mac-dev-playbook
