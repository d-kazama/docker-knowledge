<<<<<<< HEAD
# docker-knowledge
Docker file for knowledge

- This is Dockerfile that can build a docker image of [Knowledge](https://github.com/support-project/knowledge).


## What's Knowledge
- Free Knowledge Management System

- [Live Demo](https://support-project.org/knowledge/index)

- [Landing page](https://support-project.org/knowledge_info/index)



## Get from Docker Hub

```
docker pull koda/docker-knowledge
mkdir /home/hoge/knowledge
chmod a+w /home/hoge/knowledge
docker run -d -p 80:8080 -v /home/hoge/knowledge:/root/.knowledge --name knowledge koda/docker-knowledge
```



## Build yourself

Get DockerFile and run this command.

```
docker build -t knowledge .
mkdir ~/home/hoge/knowledge
chmod a+w /home/hoge/knowledge
docker run -d -p 80:8080 -v /home/hoge/knowledge:/root/.knowledge --name knowledge knowledge
```

=======
# docker-knowledge
>>>>>>> 4f217f9a2f3c0e4a2230e266cc501a95993b360d
