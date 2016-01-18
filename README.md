# Docker Rails App Container

_Docker Rails App Container_ is a small project giving you the essential tools to get started with Rails development.

## Getting started

Getting started is as easy as cloning this repository and running a few Docker commands

```
git clone <git repo url>
cd docker-rails-app
docker-compose run --rm web bundle install
docker-compose run --rm web rails new .
docker-compose up
```