# Ansible test bench

This repo consists of an ansible project (with a complete folder structure) and some docker and
docker-compose maginc to allow the ansible code to run on small docker images, allowing ansible
tests on multiple hosts to be very easy.

# Usage

- Change something in ansible you want to try out
- Run the appropriate playbook.

Run syntax :

```bash
docker-compose run --rm ansible ansible-playbook -i inventories/[environment] [playbook].yml
```

# Example

Running on `production` inventory the `web` playbook :


```bash
docker-compose run --rm ansible ansible-playbook -i inventories/production web.yml

```
