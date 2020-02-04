# singularity-docker-centos7-conda-pytorch with shapegan
centos7 container with miniconda and pytorch + pip install requirements from https://github.com/marian42/shapegan (re-using the container built from https://github.com/truatpasteurdotfr/singularity-docker-centos7-conda-pytorch).


Building: (you MUST adapt the path to the local .sif file) 
```
sudo singularity build singularity-localimage-shapegan.sif Singularity
```
