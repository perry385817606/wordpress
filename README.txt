
基于centos7的官方镜像构建的镜像，
环境为LNMP,在此基础上安装了wordpress

Dockerfile构建:
docker build --rm -t wordpress:v1 .

构建完成后查看镜像
docker images

启动镜像
docker run -d --restart always -p 80:80 containerID


访问站点
http://ip-address/

数据库密码及wordpress的在容器中