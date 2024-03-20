# Model Deployement Using Docker

## Run Using Docker Compose

```bash
docker-compose up
```

## Run Without Make

- Run the following command to build the docker image

```bash
docker build -t flask-image .
```

- Run the following command to run the docker container

```bash
docker run -d -p 8081:8081 flask-image
```

OR

## Run Using Make

- Build docker container

```bash
make build
```

- Run docker container

```bash
make run
```
