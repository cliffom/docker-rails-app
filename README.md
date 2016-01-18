# Docker Rails App Container

_Docker Rails App Container_ is a small project giving you the essential tools to get started with Rails development.

## Getting started

Getting started is as easy as cloning this repository and running a few Docker commands

```
git clone git@github.com:cliffom/docker-rails-app.git
cd docker-rails-app
docker-compose run --rm web rails new .
docker-compose run --rm web rails s -b 0.0.0.0
```
