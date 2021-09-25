Chuck Norris Facts
=========

Playbook exemple:

```
- name: Citation
  hosts: localhost
  connection: local
  become: no
  collections:
    - quanticware.citations
  tasks:
    - name: SUCCESS
      include_role:
        name: chucknorris
      vars:
        name: Marcel
        language: fr
```
