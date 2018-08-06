# Ansible role for goss & dgoss installation

This role will install hadolint docker linter.
# Usage example
    ansible-galaxy install renderqwerty.dgoss

Add this to your playbook:

    - name: install dgoss to localhost
      hosts: localhost
      connection: local
      become: yes
      gather_facts: true
      roles:
        - renderqwerty.dgoss

# License

MIT License

# Author

http://github.com/RenderQwerty/
