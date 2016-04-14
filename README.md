# Vagrantfile

This is to set up Vagrant box using ubuntu 14.04 trusty.

All steps you have to do in order to create a running vm with docker engine and docker-compose are:

```
git clone https://github.com/alfredoreduarte/vagrant_docker.git 
mv vagrant_docker installthisapp
cd installthisapp
vagrant up
vagrant ssh
docker run hello-world
```

# init.sh

Docker-engine and docker-compose are installed to be ready by vagrant user.
