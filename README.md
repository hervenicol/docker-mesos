# docker-mesos
Mesos container with docker support.

Please use docker-mesos-master and docker-mesos-slave rather than docker-mesos.


I was trying to deploy mesos in Docker containers, to orchestrate docker containers, while using a recent version of Mesos.


The latest possible and most official Mesos container can be found here:
https://hub.docker.com/r/mesosphere/mesos/

...but it lacks docker support.


These images (docker-mesos, docker-mesos-master and docker-mesos-slave) are built on top of theirs, adding Docker support.
