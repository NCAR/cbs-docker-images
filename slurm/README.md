# Slurm


The scripts in `slurm` directory used to create pbs docker image belong to  [dask-jobqueue](https://github.com/dask/dask-jobqueue) project.

# Build and push image to DockerHub

```console
$ docker build -t andersy005/slurm .

$ docker login -u $DOCKER_LOGIN -p $DOCKER_PASSWORD
$ docker push andersy005/slurm
```


# Build slurm and run slurm docker image

```console
$ ./start-slurm.sh
$ cd -
$ docker ps -a
$ docker images
```

