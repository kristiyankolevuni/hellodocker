# hellowhale

This is built for a quick demonstration.

Pre-requisite

- Install Docker


## Clone the Repository

```
git clone https://github.com/kristiyankolevuni/hellodocker
```

## Building the Image

```
cd hellodocker
docker build -t hellodocker .
```

## Running the Docker Container

```
docker run -d -p 80:80 --name hellodocker hellodocker
```

## Tagging the Image

```
docker tag hellodocker [DockerHub username]/hellodocker
```

## Pushing it to Dockerhub

```
docker login
```

```
docker push [DockerHub username]/hellodocker
```
