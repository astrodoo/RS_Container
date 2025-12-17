
### Building an image
sudo apptainer build myConda_yaml.sif myConda.def > myconda_yaml.log

### Execution sample
apptainer exec myConda_yaml.sif python3 -c "import numpy; print(numpy.__version__)"
