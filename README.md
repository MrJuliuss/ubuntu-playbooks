Ubuntu playbooks
================

Ansible playbooks for ubuntu (desktop)

### Roles

* [apache](roles/apache)
* [composer](roles/composer)
* [git](roles/git)
* [lilyterm](roles/lilyterm)
* [mysql](roles/mysql)
* [nodejs / npm](roles/node)
* [php for apache](roles/php-apache)
* [sublime text 3](roles/sublime-text)
* [zsh](roles/zsh)
* [zeal documentations](roles/zeal)


### Launch Ansible in local

  ansible-playbook -i hosts playbook.yml --connection=local --ask-sudo-pass
