# PBS


The scripts in `pbs` directory used to create pbs docker image belong to  [dask-jobqueue](https://github.com/dask/dask-jobqueue) project.

# Build and push pbs docker image to DockerHub

```console
$ docker build -t andersy005/pbs .

$ docker login -u $DOCKER_LOGIN -p $DOCKER_PASSWORD
$ docker push andersy005/pbs
```


# Build and run pbs docker image

```console
$ ./start-pbs.sh
$ cd - 
$ docker exec -it -u pbsuser pbs_master pbsnodes -a
$ docker ps -a
$ docker images
```

