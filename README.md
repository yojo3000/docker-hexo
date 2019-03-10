## 測試環境: Ubuntu 18.04 Server x64 on ESXI

Install Docker on Ubuntu:
<br>
[Document Link](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
<br><br>
Install pip3:
```
curl https://bootstrap.pypa.io/get-pip.py | python3
```
<br><br>
Install docker-compose:
```
pip3 install docker-compose
```
<br><br>
Pull docker image:
```
docker pull yojo3000/hexo
```
<br><br>
Or build the image yourself:
```
docker build . -t whatever/name_youwant
```
<br><br>
Turn on docker-compose from this repo:
```
docker-compose up
```
<br><br>
Visit Pritunl from browser:
```
https://ip_address:4000
```
<br><br>
Enter docker container by container_name (pritunl):
```
docker exec -it hexo /bin/bash
```
<br><br>
Do Whatever you want with hexo command
<br>
[Hexo Document](https://hexo.io/zh-tw/docs/commands)
