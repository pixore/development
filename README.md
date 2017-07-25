# Pixore development

## Getting started

```sh
git clone https://github.com/Pixore/development.git pixore-dev && cd pixore-dev
git submodule init && git submodule update
git submodule foreach npm install
docker-compose build
docker-compose up -d
open http://localhost:8000
```
And open [http://localhost:8000](http://localhost:8000)

## Add a new submodule

```sh
git submodule add https://github.com/pixore/<submodule_name>.git
cd <submodule_name> && npm install
```
