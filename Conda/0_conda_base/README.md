# Build the container 

## set the tmp diroectory
export APPTAINER_TMP=$HOME/Containers/tmp

## add the flag -E to pass environment variable
sudo -E apptainer build anaconda_base.sif anaconda_base.def > anaconda_base.log
