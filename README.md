# users_fastapi

users app using fast api

# Setup

> cloning
>
> `git clone <url-app>`
>
> `git fetch origin`

> setting up virtual environment
>
> `python -m venv venv`

> activate
>
> `source venv/bin/activate`

> install requirements.txt
>
> `pip install requirements.txt`

> run server
>
> `uvicorn main:app --reload`

# Docker Setup

Running Locally on Docker port 8000

> run server
>
> `make build`

> stop server
>
> `make down`

## Tech Stack

database: PostgreSQL framework: FastAPI language: Python

## Objective

- Create a USER built REST API using FastAPI
- Users can create accounts persiting data to database and retured an auth token for access

Practice

1. building routes
2. sending and recieving data
3. authenticating and granting access via tokens
4. Dockerize app

## Extra

1. Build CI/CD Pipeline
2. Deploy to AWS

# Docker setup

Local configuration yaml file
.envs are now sorted
requirements splitting for local and production configurations
