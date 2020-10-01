=====================================================
		Mise en pratique des acquis
		ESGI - 4ème année IW 2020
=====================================================

# Installation

Run:

```bash
$ docker-compose up

You are done, you can visit your Symfony application on the following URL: `http://symfony.localhost` 

```bash
$ docker-compose build

# How it works ?

Here are the `docker-compose` built images:

* `db`: This is the MySQL database container (can be changed to postgresql or whatever in `docker-compose.yml` file),
* `php`: This is the PHP-FPM container including the application volume mounted on,
* `nginx`: This is the Nginx webserver container in which php volumes are mounted too,




