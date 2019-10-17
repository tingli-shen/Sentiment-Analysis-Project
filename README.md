# Sentiment-Analysis-Project
### Set up Hadoop environment with Docker
```
$ mkdir bigdata-class2
$ cd bigdata-class2 
$ sudo docker pull joway/hadoop-cluster # download Hadoop image from dockerhub
$ git clone https://github.com/joway/hadoop-cluster-docker 
$ sudo docker network create --driver=bridge hadoop 
$ cd hadoop-cluster-docker
$ sudo ./start-container.sh # enter docker container
$ ./start-hadoop.sh # run hadoop
```
