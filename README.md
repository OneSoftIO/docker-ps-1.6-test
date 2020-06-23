# docker-ps-1.6-test

# Setup

## Requirements

1. Docker 17.06.0+
2. docker-compose

## Running first time

In order to run containers first time:

* Open console
* Go to root directory
* Write to console :
    1. if you want to see output `docker-compose up --build` 
    2. if you want detached service `docker-compose up --build -d`
* Whenever job is done and containers aren't needed anymore:
    1. If container output was attached click CTRL + C and wait till containers shutdown gracefully.
    1. If container output was detached go to rood dir and write `docker-compose down` and wait till containers shutdown gracefully.

# Running already created containers

In order to run already setup containers:

* Open console
* Go to root directory
* Write to console :
    1. if you want to see output `docker-compose up` 
    2. if you want detached service `docker-compose up -d`
* Whenever job is done and containers aren't needed anymore:
    1. If container output was attached click CTRL + C and wait till containers shutdown gracefully.
    1. If container output was detached go to rood dir and write `docker-compose down` and wait till containers shutdown gracefully.
