# Containers

This repository will contain all containers I will run for my projects. I will build them using `buildx` which is a Docker command that can be used to build containers for both the amd64 and amr64 architecture. This means that the containers should work both on Mac and on servers and Windows machines.

Each container is pushed to Docker hub where it can be pulled in my [repository](https://hub.docker.com/repositories/mnytaqw).

Each container can be pulled and converted to an Apptainer container using a command like this `apptainer pull container.sif docker://mnytaqw/quarto_jupyter_base:latest`.

