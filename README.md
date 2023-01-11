# Golang Application Demo

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
