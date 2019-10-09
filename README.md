# Docker image with PHPQA and Drupal, DrupalPractice ruleset

![Ecedi Agency](https://www.ecedi.fr/theme/images/logo-ecedi-top.png)

**This is image is based on the official docker image php72-alpine <https://hub.docker.com/_/php>.**

## Documentation

Documentation is available at [docker hub](https://hub.docker.com/r/ecedi/phpqa).

## Requirement

Docker and/or docker-compose installed on your system.

## Installation

```bash
docker run --rm -it ecedi/phpqa phpqa tools
# using a tool without phpqa
docker run --rm -it ecedi/phpqa phpcs -i
```

## Ecedi Community Support

Have a question?  Contact us [Email LD](mailto:ld@ecedi.fr)
