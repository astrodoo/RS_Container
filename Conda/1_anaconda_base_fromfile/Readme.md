# Build the container 

## set the tmp diroectory
export APPTAINER_TMP=$HOME/Containers/tmp

## add the flag -E to pass environment variable
sudo -E apptainer build anaconda_base_fromfile.sif anaconda_base_fromfile.def > anaconda_base_fromfile.log
