RHCI Docker Hackathon
=====================

This repo contains materials for running Red Hat components on Docker and Kubernetes.  Please create a child directory with your project name and the following contents:

* README.md - markdown document describing how someone can try out your images
* Dockerfiles
* Kubernetes pod or replication controller descriptions as JSON files

Please push your docker images to http://registry-origin.itos.redhat.com under a repository matching your project name:

    $ docker tag myimage registry-origin.itos.redhat.com/myproduct/myimagename
    $ docker push registry-origin.itos.redhat.com/myproduct/myimagename

