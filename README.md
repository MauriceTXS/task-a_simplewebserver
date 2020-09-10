# Simple web server

Using Nginx for a reverse proxy and for two other webservers running on different ports.

The first web server can be found at `/` and the second can be found at `/webserver2`.

## Instructions

1. `docker-compose build`
2. `docker-compose up -d`
3. Visit [localhost](http://localhost)