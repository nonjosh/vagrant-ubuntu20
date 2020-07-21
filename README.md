# vagrant-ubuntu20

Vagrantfile with my personal customized setting

## Settings

bridged network with static ip

installed softwares:

- docker
- docker-compose
- tmux
- net-tools libpq-dev python3-dev
- miniconda

version:

```sh
vagrant@ubuntu-bionic:~$ conda --version && docker --version && docker-compose --version
conda 4.3.30
Docker version 19.03.12, build 48a66213fe
docker-compose version 1.24.1, build 4667896b
```

## How to use

Install [Vagrant](https://www.vagrantup.com/downloads.html)

Navigate to the `ubuntu-server` or `ubuntu-desktop` directory

Start the VM

```sh
vagrant up
```

SSH into the VM

```sh
vagrant ssh
```
