# alpine-psql
A docker image based on alpine with a PostgreSQL client added.

Is usefull in case you're using init containers on k8s to prepare your database before the container with your micro service is started. Will reduce the start time of the micro service, because there's no need anymore to download the psql client.
