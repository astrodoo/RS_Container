# Build the container 

### set the tmp directory
```shell
export APPTAINER_TMP=$HOME/Containers/tmp
```

### add the flag -E to pass environment variable
```shell
sudo -E apptainer build first_anaconda_0.sif first_anaconda_0.def > first_anaconda_0.log
```
