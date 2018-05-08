# ansible

### Usage

In playbook:

    - name: Playbook
      roles:
        - role: ansible

Include in `requirements.yml`:

    - src: https://github.com/uZer/ansible-role-ansible.git
      name: uZer.ansible
      version: latest

Install/Force update:

    ansible-galaxy install -r requirements.yml --force

### Variables

TBD.

### License

* `BY-SA` – [Attribution-ShareAlike](https://creativecommons.org/licenses/by-sa/4.0/)
