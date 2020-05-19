# Ansible Role: docker
Installs docker from official sources

## Requirements
None

## Role Variables
- `docker_old_packages`: List, packages to remove
- `docker_dependencies`: List, of dependency packages to install
- `docker_packages`: List, of docker packages to install
- `docker_user`: String, name of the docker user
- `install_compose`: Boolean, Install docker-compose?
- `compose_url`: String, URL to fetch docker-compose
- `compose_path`: String, path to install docker-compose

## Dependencies
None

## Example Playbook

    - hosts: servers
      roles:
         - docker

## License
MIT

## Author Information
[Jon Ball](mailto:jonathon.ball@gmail.com)
