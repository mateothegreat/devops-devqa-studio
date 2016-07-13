# devops-devqa-studio
100% Web based Development Environment

## Requirements
- [The Docker Platform](https://www.docker.com/products/overview#/install_the_platform)

## Installation
1. `git clone --recurse-submodules https://github.com/mateothegreat/devops-devqa-studio.git`
2. `cd devops-devqa-studio/bin && ./build.sh && ./ide-start.sh`

By default, source files reside on the filesystem of the host (i.e.: the vm in virtualbox, aws, etc.) and are "virtually mounted" on the filesystem inside of the docker container as /home/$USER/workspace *([see Dockerfile#L31](https://github.com/mateothegreat/devops-docker-cloud9/blob/master/Dockerfile#L31))*.

The ide will be available on port 80 and is listening on all interfaces (to get you started, you can edit the ide-start.sh script or rebuild the docker image to change any setting docker has available).
![What you should see.](https://lh3.googleusercontent.com/-hWpilJrkgqs/V2KwrvAtnaI/AAAAAAAAAGQ/b6pekvKTsuk/s0/chrome_2016-06-16_06-59-09.jpg)

## Help
Open up an issue or ping me @appsoa on skype (I welcome the testing exercices as we build).
