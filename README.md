# Sentiment-Analysis-Project
### Set up Hadoop environment with Docker
```
$ mkdir bigdata-class2
$ cd bigdata-class2 # 上两条命令是创建一个目录
$ sudo docker pull joway/hadoop-cluster # download Hadoop image from dockerhub
$ git clone https://github.com/joway/hadoop-cluster-docker get code from github
$ sudo docker network create --driver=bridge hadoop 
```
