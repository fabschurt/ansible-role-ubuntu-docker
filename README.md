# Ubuntu Docker (16.04)

[![Travis CI](https://img.shields.io/travis/fabschurt/ansible-role-ubuntu-docker.svg)](https://travis-ci.org/fabschurt/ansible-role-ubuntu-docker)

This role will set your Ubuntu box up for running Docker containers. Nothing
really fancy here, it just follows the instructions given in the official
[installation documentation](https://docs.docker.com/engine/installation/linux/ubuntulinux/).
It will also install the latest version of Docker Compose.

Full compatibility has been tested on **Ubuntu 16.04** only.

## Requirements

* Ubuntu remote host(s) with root access
* Ansible >= 2.1

## Example playbook

This is an example playbook that demonstrates how you would use the role, provided
that you’ve [installed](https://galaxy.ansible.com/intro#download) it already&nbsp;:

```yaml
- hosts: servers
  roles:
    - role: fabschurt.ubuntu-docker
```

## License

This software package is licensed under the [MIT License](https://opensource.org/licenses/MIT).
