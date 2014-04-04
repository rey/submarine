# submarine

## About

This is a dummy repo that aims to provide a generic environment to run Jekyll in
an Ubuntu VM running on Vagrant with VirtualBox.

## Prerequisites

* VirtualBox (4.3.12)
* Vagrant (1.5.1)

## Get started

1. Clone the repo

        git clone https://github.com/rey/submarine.git ~/your-project

2. `cd ~/your-project`
3. `vagrant up`
4. `vagrant ssh`

## Start Jekyll

### On the VM

1. `cd /vagrant`
2. `bundle`
3. `foreman start`

Jekyll has started! Visit `localhost:1122` in your browser for good time.

## If you're using a GUI text editor or want to work on the host machine

### On the host machine

1. `cd ~/your-project`
2. `vagrant rsync-auto`

You can now make changes to files at `~/your-project` on the host machine and
they will be automagically rsynced to the host VM.
