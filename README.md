# rails5-docker-template
Rails5 template on the docker container

## Description

This is the application template for Rails5 project that works on docker container.

## Requirements

This template currently works with:

- Ruby 2.7.1
- Rails 5.2.4.3
- MySQL 5.7.31

If you'd like to change minor version,  you can change the configuration file below:

- Dockerfile
- Gemfile
- docker-compose.yml

## Usage

All you have to is to run below if you’ve installed this template as default 

```
$ docker-compose build
$ docker-compose up
```

If you'll install another gem packages, you fix the Gemfile and the run `bundle install`
