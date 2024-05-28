## machine_learning_dev
需要将最新版本的pycharm解压并重命名为pycharm，然后拷贝到software目录下
docker build  -f  Dockerfile -t ubuntu_desktop_hou:conda_jupyter_pycharm  .
## 编译镜像



## 启动命令

docker run --gpus all -d --net=bridge --restart always --name ubuntu_desktop_hou -d -p 10001:10001 -p 10002:80 -p 10003:5900 -e RESOLUTION=1920x1080 -e VNC_PASSWORD=hou -v /home:/home -v /dev/shm:/dev/shm houbenzhou/ubuntu_desktop:hou_2004_cudabase102_v3_2020_10_15

sudo docker run --rm -it --shm-size=512m -p 6903:6901 -e VNC_PW=hou 