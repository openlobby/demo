# Open Lobby Demo

Demo of [Open Lobby Server](https://github.com/openlobby/openlobby-server) and
[Open Lobby App](https://github.com/openlobby/openlobby-app).

You need [Docker Compose](https://docs.docker.com/compose/) for running this
demo.

## Run

Clone this repository and then you can:
- Run it: `make run`
- Stop it: `make stop`
- Stop and/or remove all data: `make destroy`

It runs:
 - Elasticsearch on port `9200`
 - Open Lobby Server on port `8010` - GraphQL API endpoint and GraphiQL
   interface are at `http://localhost:8010/graphql`
 - Open Lobby App on port `8020` - web application is at `http://localhost:8020`

You may notice some errors and crashes if you access it immediately because
Elasticsearch starts slowly. But it should recover and eventually it will be all
running fine.
