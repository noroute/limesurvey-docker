= LimeSurvey Docker container

A LimeSurvey installation trying to re-use existing building blocks!

== Get started!

 * ``docker-compose up -d``
 * ``docker-compose logs | grep "GENERATED ROOT PASSWORD"

Copy the generated root password, navigate to your docker-machine IP address.

DB hostname is 'db', password is as copied.

== Compatibility
 * Docker >=1.10 (docker-compose v2 format)
 * Docker-Compose >=1.6

== NOTES
The database contents is held in a local docker volume.
