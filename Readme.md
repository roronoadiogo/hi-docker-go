# Hello World GoLang with Docker
It's a simple project to try to understand how works the Dockerfile with Golang.
Execute a simple endpoint using Echo library.

## Setup

- GoLang version 1.20
- Docker

## Run

Execute the command in the root of project:

```sh
docker build -t hi-docker-go .
```

and

```sh
docker run hi-docker-go
```

in another terminal, run this command to see a message:

```sh
curl localhost:8080/
```

or to receive a status in the terminal

```sh
curl localhost:8080/ping
```

Go go go!