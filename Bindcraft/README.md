

### Set the environment
export APPTAINER_TMPDIR=$HOME/Containers/tmp

### Build an image
sudo -E apptainer build bindcraft.sif docker://yarrowdocker/bindcraft
