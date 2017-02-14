# Docker Compose Volumes with V3

Trying to get an Nginx/PHP FPM setup, sharing the volume from PHP with Nginx and while using compose version 3 syntax.

## Usage

1. Check it out
1. Run `docker-compose up -d` from the repo
1. Go to http://localhost:8888 and you will see an unstyled page with a PHP version.
1. If you try to [load the CSS stylesheet](http://localhost:8888) the CSS is marked 404 because Nginx cannot see it.
