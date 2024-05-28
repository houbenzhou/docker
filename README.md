# docker
docker build  -f  Dockerfile -t ubuntu_desktop_hou_machine_learning_dev:test  .


## 

sudo docker run --rm -it --shm-size=512m -p 6903:6901 -e VNC_PW=hou kasmweb/core-cuda-focal:1.15.0-rolling

sudo docker run --rm -it --shm-size=512m -p 6901:6901 -e VNC_PW=hou kasmweb/core-cuda-focal:1.15.0-rolling

