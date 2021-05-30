# jupyter-on-docker-

#after creating the dockerfile use the below command to build a os from that dockefile 

$ docker build -t docker_gui/jupyter 

#after the successfull creation of docker image use the below command to launch a container and enjoy jupyter on docker

$ docker run -it -v /tmp/.X11-unix:/tmp/.X11-unix -e DISPLAY=:0 docker_gui/jupyter
