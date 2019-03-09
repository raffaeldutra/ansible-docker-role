# Ansible Role: Docker

Install Docker and configure Swarm Cluster.

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

In you are using Vagrant, include remote_usere: vagrant.

```
  - name: Docker
    hosts: docker
    become: yes
    roles:
      - docker
```

## License
-------

MIT / BSD

Author Information
------------------

Rafael Dutra <raffaeldutra@gmai.com>
@raffaeldutra
https://rafaeldutra.me
https://hub.docker.com/u/raffaeldutra
https://linkedin.com/in/rafaeldutra
https://github.com/raffaeldutra
https://gitlab.com/raffaeldutra
https://speakerdeck.com/raffaeldutra