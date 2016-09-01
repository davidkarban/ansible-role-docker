#  Ansible Role for Docker


Ansible Role for DockerInstallation.   ( work-in-progress )

##  Requirements

This role require Ansible 2.0 or higher.

This role was designed on Ubuntu 16.04 LTS and Centos 7. 

## Role Variables

Check `defaults/main.yml`

##  Dependencies

Jinja `combine` filter - contained in Ansible 2.0.

##  Example Playbook

    - hosts: all
      roles:
        - role: docker

## License

-   Code released under [MIT](https://github.com/pantarei/ansible-role-postgresql/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

### Author Information

- [Veros Kaplan](https://github.com/verosk/)
- Sponsored by [Twisto](http://twisto.cz/)

