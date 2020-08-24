# Docker

### Usefull commands
```
Docker images – Will present the images available
Docker ps – To check the containers running
Docker ps -a– To check every container running including hidden files
Docker pull – to pull the image from docker hub
Docker run – to run the image live directly from dockerhub

```

### Pushing to Docker

##### 1) Log into your Docker account using the following command:

```docker login```

##### 2) View the Images available by typing, The image I copyed was for nginx. 

```docker images```

##### 3) Next use the following command. This works in a similar way to git add .

```docker tag 4bb46517cac3 danteegan/daniel-teegan-eng-67:First_commit_docker (Use image ID not container ID)```

##### 4) Now to push we use the following command. It is docker push then your docker account name followed by the repo you want to push too

```docker push danteegan/daniel-teegan-eng-67```

##### 5) Your image sould now be pushed onto docker!!

### Pulling from Docker

##### 1) To pull a repo from docker use the following command

``` docker run -d -p 90:80 bariallali/bari-docker-eng67:Second_commit_adding_nginx_image ```

##### When pulled on your local host port 90 It should show the image in this case nginx
