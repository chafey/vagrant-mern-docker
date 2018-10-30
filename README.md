# vagrant-mern-docker
Vagrant for building mern applications with docker 

Startup vagrant and prepare source tree

Terminal One:

> vagrant up

> cd src

> git clone <your git repo>

> vagrant ssh

> cd src

## run your application listening on port 9000

Open the meteor app in your web browser running on the host:

> open http://localhost:9000/

NOTE: you can run vagrant rsync-auto in another terminal to synchronize source changes made in the host to the guest.  This
can be useful when you want to use an editor on your host (e.g. Visual Studio Code).  And then run vagrant-rsync-auto to sync
 changes from host to guest

Terminal Two: 

> vagrant rsync-auto

