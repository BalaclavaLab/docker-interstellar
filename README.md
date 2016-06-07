# docker-interstellar
Docker container with [interstellar](https://github.com/ccyanni/interstellar) app.

Put your secrets.yml and .boto files to some "secrets" directory and run container as:

`docker run -d  --volume "$PWD"/secrets:/usr/src/interstellar/secrets balaclavalab/docker-interstellar`

