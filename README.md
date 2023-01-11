# Golang Application Demo

Requires the following to run:

  * [Docker][docker]
  * [Docker Compose][Docker Compose]


[docker]: https://docs.docker.com/get-docker/
[Docker Compose]: https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-compose-on-ubuntu-20-04

------------

### Clone Repo

```
git clone https://github.com/ricardo-souza-dev/golang.git
```

### Enter Directory

```
cd golang
```

### Run Application

```
docker-compose up
```

------------

### Create Fact

```
curl --location --request POST 'http://127.0.0.1:3000/fact' \
--header 'Content-Type: application/json' \
--data-raw '{
    "question":"O que é isso?",
    "answer":"Isso é alguma coisa!"
}'
```

### List Facts

```
curl --location --request GET 'http://127.0.0.1:3000/'
```
