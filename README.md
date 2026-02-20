# [Ansible role apache-php-fpm-back](#ansible-role-apache-php-fpm-back)

Apache 2.4+ PHP-FPM support for Linux.

|GitHub|GitLab|Downloads|Version|
|------|------|---------|-------|
|[![github](https://github.com/buluma/ansible-role-apache-php-fpm-back/workflows/Ansible%20Molecule/badge.svg)](https://github.com/buluma/ansible-role-apache-php-fpm-back/actions)|[![gitlab](https://gitlab.com/shadowwalker/ansible-role-apache-php-fpm-back/badges/master/pipeline.svg)](https://gitlab.com/shadowwalker/ansible-role-apache-php-fpm-back)|[![downloads](https://img.shields.io/ansible/role/d/buluma/apache-php-fpm-back)](https://galaxy.ansible.com/buluma/apache-php-fpm-back)|[![Version](https://img.shields.io/github/release/buluma/ansible-role-apache-php-fpm-back.svg)](https://github.com/buluma/ansible-role-apache-php-fpm-back/releases/)|

## [Example Playbook](#example-playbook)

This example is taken from [`molecule/default/converge.yml`](https://github.com/buluma/ansible-role-apache-php-fpm-back/blob/master/molecule/default/converge.yml) and is tested on each push, pull request and release.

```yaml
---
- name: Converge
  hosts: all
  become: true
  gather_facts: true

  # roles:
  #   - role: buluma.apache_php_fpm_back
```

Also see a [full explanation and example](https://buluma.github.io/how-to-use-these-roles.html) on how to use these roles.


## [Requirements](#requirements)

- pip packages listed in [requirements.txt](https://github.com/buluma/ansible-role-apache-php-fpm-back/blob/master/requirements.txt).

## [State of used roles](#state-of-used-roles)

The following roles are used to prepare a system. You can prepare your system in another way.

| Requirement | GitHub | GitLab |
|-------------|--------|--------|
|[geerlingguy.apache](https://galaxy.ansible.com/buluma/geerlingguy.apache)|[![Build Status GitHub](https://github.com/buluma/geerlingguy.apache/workflows/Ansible%20Molecule/badge.svg)](https://github.com/buluma/geerlingguy.apache/actions)|[![Build Status GitLab](https://gitlab.com/shadowwalker/geerlingguy.apache/badges/master/pipeline.svg)](https://gitlab.com/shadowwalker/geerlingguy.apache)|

## [Context](#context)

This role is part of many compatible roles. Have a look at [the documentation of these roles](https://buluma.github.io/) for further information.

Here is an overview of related roles:
![dependencies](https://raw.githubusercontent.com/buluma/ansible-role-apache-php-fpm-back/png/requirements.png "Dependencies")

## [Compatibility](#compatibility)

This role has been tested on these [container images](https://hub.docker.com/u/buluma):

|container|tags|
|---------|----|
|[EL](https://hub.docker.com/r/buluma/enterpriselinux)|all|
|[Debian](https://hub.docker.com/r/buluma/debian)|all|
|[Ubuntu](https://hub.docker.com/r/buluma/ubuntu)|all|

The minimum version of Ansible required is 2.0, tests have been done on:

- The previous version.
- The current version.
- The development version.

If you find issues, please register them on [GitHub](https://github.com/buluma/ansible-role-apache-php-fpm-back/issues).

## [License](#license)

[license (BSD, MIT)](https://github.com/buluma/ansible-role-apache-php-fpm-back/blob/master/LICENSE).

## [Author Information](#author-information)

[geerlingguy](https://buluma.github.io/)

