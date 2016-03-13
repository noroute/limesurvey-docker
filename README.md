# LimeSurvey Docker container

A [LimeSurvey](https://www.limesurvey.org/) installation trying to re-use existing building blocks!

## Get started!

 * ``docker-compose up -d``
 * ``docker-compose logs | grep "GENERATED ROOT PASSWORD"``

Copy the generated root password, navigate to your docker-machine IP address.

DB hostname is 'db', password is as copied.

## Compatibility
 * Docker >=1.10 (docker-compose v2 format)
 * Docker-Compose >=1.6

## NOTES
 * ``limesurvey-docker`` uses the [mysql:5.7.11](https://github.com/docker-library/mysql/blob/4e022c06314ff6047dabc4abee2f222ae9ce564d/5.7/Dockerfile) container.
 * The database' contents is held in a local docker volume.
