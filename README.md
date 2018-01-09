# test-apb - repo for experimenting with apb

## How to use this?

1. Clone this repo
1. [Install apb](https://github.com/ansibleplaybookbundle/ansible-playbook-bundle/blob/master/docs/getting_started.md#getting-started)
1. Edit [Makefile](https://github.com/psturc/test-apb/blob/master/Makefile) (set your own DOCKERHOST, DOCKERORG, IMAGENAME)
1. Run `make` inside this repo to build this apb, push it to your Docker registry and OpenShift Service Catalog
1. Run `apb test`
