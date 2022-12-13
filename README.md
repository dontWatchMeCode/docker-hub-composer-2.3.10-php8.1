# docker-image-composer-2.3.10-php8.1

Custom docker image for composer 2.3.10 with php 8.1 based on the [official](https://github.com/composer/docker) composer image.

[Docker Hub link](https://hub.docker.com/r/mgschwandtner/composer-2.3.10-php8.1)

## Usage

```sh
# version 1.0.1
docker run -it mgschwandtner/composer-2.3.10-php8.1:1.0.1
```

## deploying a new version

```sh
# build the image
docker build -t mgschwandtner/composer-2.3.10-php8.1:{TAG}

# push the image to docker hub
docker push mgschwandtner/composer-2.3.10-php8.1:{TAG}
```