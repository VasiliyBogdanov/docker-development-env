### Important:
This is practice repo. \
Focus was on development environment **only**.

### Description:
The point of this repo is to make containerized *development* environment, 4th project from Hexlet school was chosen as guinea pig. \
Server is dockerized, it uses project folder as volume, so all changes are reflected immediately. \
Postgres was chosen as db, as it was used in initial project.


### Prerequisites:
Docker

### Local installation:
1. Clone this project or download zip.
2. Create .env file in root directory. \
Instructions are in .env.example file.
3. To start environment:
```
docker compose up
```
4. To stop environment:
```
docker compose down
```

By default server is available on 0.0.0.0:8000