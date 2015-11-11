docker-carton
=============

Docker build: Carton on perl:5.22.0 on Debian testing

* * *

https://registry.hub.docker.com/u/merrilymeredith/carton/

Simply adds the latest Carton onto library/perl:latest, which is built on
Debian (aka buildpack-deps:latest).  With Carton, you can prep your perl
dependencies in another layer, without depending on distro packages.

I didn't want to mess with Ubuntu or CentOS builds or unnecessary use of
perlbrew/plenv.

