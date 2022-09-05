# NodeGoat

Fork of [OWASP Nodegoat](https://github.com/OWASP/NodeGoat) to install Datadog ASM.

## Setup

- Copy `.env.example` to `.env` and populate your datadog site name and API key.

- `docker-compose build web` to build the web application

- `docker-compose up -d` to start the containers

- Open a browser at port 4000 localhost and go from there, the application just works as Nodegoat.