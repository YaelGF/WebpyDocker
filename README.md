# WebpyDocker

Introduction in docker used webpy MVC# Titule

# How to Install


``` shell
git clone https://github.com/YaelGF/WebpyDocker.git
```

``` shell
cd docker
docker built -t webpy:v1 .
```

``` shell
cd ..
docker run -it -v $(pwd)/WebpyDocker:/WebpyPage -p8080:8080 --name webpy -h python webpy:v1
```

``` shell
docker start -i webpy
cd WebpyPage
python3 app.py
```

# Run the project

## Containers
![containers](/assets/contenedores.png)

## Docker
![docker](/assets/docker.png)

## Ubuntu
![ubuntu](/assets/Ubuntu.png)


# License
[Apache License 2.0](https://github.com/YaelGF/WebpyDocker/blob/main/LICENSE)