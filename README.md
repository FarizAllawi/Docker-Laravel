# Schema Details

This is a Docker Compose schema that can be used to run Laravel.
Several programs used include:

- NGINX
- PHP 8.4
- Supervisor
- xdebug
- Laravel Version 12
- NodeJS: npm, pnpm
- Postgresql-18


# How to Use

- Make sure you have installed Docker and Docker Compose on your computer.
- Download or clone this repository.
- Open a terminal and navigate to the directory where you saved these files.
- Update default environtment if neeed located in "docker/default.env"
- Run the following command to build and start the containers:
```bash
    docker compose up
```

Once the containers are running, open your browser and go to http://localhost to view the running Laravel application.

Dont forget to configure the environtment variables in `docker-compose.yml` file according to your needs, especially the database section.
