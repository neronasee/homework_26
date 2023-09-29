# Homework 26 - CI/CD

Setup CI/CD for your pet project or project  based on laradock

## How to run

- push into `master` branch
- run manually with `Run workflow`

## Setup

The CI/CD flow can be seen in [Actions](https://github.com/neronasee/homework_26/actions/runs/6356181213) tab

During it we:

1. Test the code (running dummy test)
2. Build and push Docker image to Docker hub
3. ssh into the VPS, pull the image and run it


## Required Github secrets set up for the repo:

- `DOCKER_USERNAME`
- `DOCKER_PASSWORD`
- `DOCKER_HUB_REPO`
- `REMOTE_HOST`
- `REMOTE_USERNAME`
- `SSH_PRIVATE_KEY`

## Required installed apps on the target machine

- docker