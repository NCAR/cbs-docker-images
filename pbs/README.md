# PBS


The scripts in `pbs` directory used to create pbs docker image belong to  [dask-jobqueue](https://github.com/dask/dask-jobqueue) project.


# Build pbs docker image

```console
$ ./start-pbs.sh
$ cd - 
$ docker exec -it -u pbsuser pbs_master pbsnodes -a
$ docker ps -a
$ docker images


