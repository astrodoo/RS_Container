
### Building an image
sudo apptainer build myConda_yaml.sif yConda.def > myconda_yaml.log

### Execution sample
apptainer exec MyCondaEnv.sif python3 -c "import numpy; print(numpy.__version__)"
