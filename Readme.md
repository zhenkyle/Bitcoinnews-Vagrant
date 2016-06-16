# Bitcoinnews-Vagrant

A development environment for [Bitcoinnews](https://github.com/zhenkyle/bitcoinnews_source.git) using [Vagrant](http://www.vagrantup.com/downloads.html).

## Prerequisites

You will need the following applications to setup the Bitcoinnews development environment:

- [Vagrant](http://www.vagrantup.com/downloads.html)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Git](https://git-scm.com/downloads)


## Setup

To get started with the Bitcoinnews development environment, you will first need to clone this repo and navigate into it:

```bash
git clone git://github.com/zhenkyle/Bitcoinnews-Vagrant.git
cd Bitcoinnews-Vagrant
```

You will now need a copy of Bitcoinnews itself:

```bash
git clone git://github.com/zhenkyle/bitcoinnews_source.git
```

Now we have both repos cloned, we can proceed with setting up the VM:

```bash
vagrant up
```

Once the VM has been setup, you will need to log in to the VM and setup Bitcoinnews:

```bash
vagrant ssh

# When logged into the VM...

cd code/Bitcoinnews
```
## Copyright & License

Copyright (c) 2016 Zhenkyle - Released under the [MIT license](LICENSE).
