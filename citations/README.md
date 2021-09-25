# Ansible Collection - Citations

##### Français

Collection de citations humoristiques

Idéal pour terminer un playbook dans la joie et la bonne humeur plutôt que d'avoir uniquement les stats.

Collection reservée à des formules d'humours et dérisions. Ni politique, ni religion, ni propos diffamatoires.

Merci @ [Mathieu Garcia](https://github.com/wiseflat).

##### English
Collection of humorous quotes.
Ideal to finish a playbook in joy and good mood rather than having only the stats.

Collection reserved for formulas of humor and derisions.

Neither politics, nor religion, nor defamatory remarks.

Thanks @ [Mathieu Garcia](https://github.com/wiseflat).

***v1.0:***

- Chuck Norris ( fr / en )


*Playbook example:*

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
