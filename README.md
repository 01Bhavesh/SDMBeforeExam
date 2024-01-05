# SDMBeforeExam

Hii This is My SDM Project

Git Commands for Proxy Error :

1.git config --global --unset http.proxy
2.git config --global --unset https.proxy
3.git config --global --unset core.gitproxy
4.git config --global http.proxy http://exam@192.168.10.4:808
5.git config --global credential.helper wincred
6.git config --global user.name "Abhishek Shahane"
7.git config --global user.email "abhishekshahane29@gmail.com"
8.git config --global user.password "token from github"

Docker File Text : FROM node:18 WORKDIR /app COPY package.json /app RUN npm install COPY ./app CMD node server.js

Docker Commands on EC2 Instance :

sudo apt update
mkdir foldername
cd folder
git clone "git repo url"
cd gitrepo
sudo apt install docker.io
sudo systemctl start docker or
sudo systemctl --type=service --state=running
sudo systemctl status docker
press q to go back
sudo docker build -t image_name . //(in lower case)//Remember "." is mandatory after image name
sudo docker images //to check images
sudo docker run -d -p port_number:port_number image_name
sudo docker rmi img --f //To Kill Docker Container
