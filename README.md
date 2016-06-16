# devops-devqa-studio
100% Web based Development Environment

Clone this repo & run the ide-start.sh script.
Source files reside on the filesystem of the host (i.e.: the vm in virtualbox, aws, etc.) and are "virtually mounted" on the filesystem inside of the docker container as /home/$USER/workspace *([see Dockerfile#L31](https://github.com/mateothegreat/devops-docker-cloud9/blob/master/Dockerfile#L31))*.
 
 `
./ide-start.sh
`

The ide will be available on port 80 and is listening on all interfaces (to get started, we'll lock things down in a bit).
![What you should see.](https://lh3.googleusercontent.com/-hWpilJrkgqs/V2KwrvAtnaI/AAAAAAAAAGQ/b6pekvKTsuk/s0/chrome_2016-06-16_06-59-09.jpg)
