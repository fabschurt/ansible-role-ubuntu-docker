# Ansible :: Ubuntu Docker

[![Travis CI](https://img.shields.io/travis/fabschurt/ansible-role-ubuntu-docker/master.svg)](https://travis-ci.org/fabschurt/ansible-role-ubuntu-docker)

This role will set your Ubuntu box up for running Docker containers. Nothing
really fancy here, it just follows the instructions given in the official
[installation documentation](https://docs.docker.com/install/linux/docker-ee/ubuntu/).
It will also install the latest version of Docker Compose.

## Requirements

* Ubuntu 18.04 remote host(s) with root access
* Ansible >= 2.4

## Example playbook

This is an example playbook that demonstrates how you would use the role,
provided that you’ve [installed](https://galaxy.ansible.com/docs/using/installing.html)
it already:

```yaml
- hosts: …
  roles:
    - role: fabschurt.ubuntu_docker
```

## License

This software package is licensed under the [MIT License](https://opensource.org/licenses/MIT).
