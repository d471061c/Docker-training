# 1.1
```shell
CONTAINER ID        IMAGE               COMMAND                  CREATED             STATUS                     PORTS               NAMES
d54ca54f62d3        nginx               "nginx -g 'daemon of…"   16 seconds ago      Exited (0) 3 seconds ago                       wizardly_dewdney
b7188b255411        nginx               "nginx -g 'daemon of…"   17 seconds ago      Exited (0) 3 seconds ago                       vibrant_nightingale
9aa1ae4b49d4        nginx               "nginx -g 'daemon of…"   19 seconds ago      Up 18 seconds              80/tcp              priceless_mahavira
```

# 1.2
```shell
PS C:\> docker ps
CONTAINER ID        IMAGE               COMMAND             CREATED             STATUS              PORTS               NAMES
PS C:\> docker images
REPOSITORY          TAG                 IMAGE ID            CREATED             SIZE
```

# 1.3
```shell
This is the secret message
```

# 1.4
```shell
Docker is easy
```

# 1.5
```shell
PS C:\> docker run -it --name site-reader ubuntu:latest sh -c 'apt-get update && apt-get install -y curl; echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website;'
```

# 1.6
```shell
PS C:\> docker build -t docker-clock .
PS C:\> docker run docker-clock -c
1
2
```

# 1.7
See folder 1.7 

# 1.8
See folder 1.8 
Secret: Volume bind mount is easy

# 1.9
```shell
docker run -p 80:80 devopsdockeruh/ports_exercise
```
# 1.10
See folder 1.10

# 1.11
See folder 1.11

# 1.12
appfrontend teht: 1.10
appbackend teht: 1.11

```shell
docker run -p 5000:5000 appfrontend
docker run -p 8888:5000 appbackend
```

# 1.13
See folder 1.13