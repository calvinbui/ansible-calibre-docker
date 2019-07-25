[![Build Status](https://travis-ci.com/calvinbui/ansible-calibre-docker.svg?branch=master)](https://travis-ci.com/calvinbui/ansible-calibre-docker)
![GitHub release](https://img.shields.io/github/release/calvinbui/ansible-calibre-docker.svg)
![Ansible Quality Score](https://img.shields.io/ansible/quality/42297.svg)
![Ansible Role](https://img.shields.io/ansible/role/d/42297.svg)

# Ansible Calibre

Calibre in Docker

##  Requirements

N/A

## Role Variables

`calibre_name`: Name of container

`calibre_image`: Docker image to  use

`calibre_ports`: List of ports to expose

`calibre_config_directory`: Directory to store configuration files

`calibre_environment_variables`: Docker environmental variables

`calibre_docker_additional_options`: [Additional parameters](https://docs.ansible.com/ansible/latest/modules/docker_container_module.html) to add to docker container

## Dependencies

N/A

## Example Playbook

```yaml
- hosts: servers
  become: true
  roles:
   - role: calvinbui.ansible_calibre_docker
```

## License

GPLv3

## Author Information

http://calvin.me
