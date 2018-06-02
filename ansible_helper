#!/usr/bin/env bash
docker run --rm -it \
  -v $HOME/.ssh/id_rsa:/root/.ssh/id_rsa \
  -v $HOME/.ssh/id_rsa.pub:/root/.ssh/id_rsa.pub \
  -v $HOME/Dev/Docker/ansible:/etc/ansible \
  -v $HOME/Dev/Docker/ansible/playbooks:/ansible/playbooks \
  -v /var/log/ansible/ansible.log \
  walokra/ansible-playbook "$@"