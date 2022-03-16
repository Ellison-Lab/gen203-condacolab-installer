# Generating the constructor file

```
mamba create -n constructor -c conda-forge constructor
conda activate constructor
constructor --platform linux-64
```

# Installing on colab

Running the commands below takes from 30s-60s.

```
!pip install -q condacolab
import condacolab
condacolab.install_from_url("https://github.com/Ellison-Lab/gen203-condacolab-installer/releases/download/0.1.0/gen203_condacolab-0.1.0-Linux-x86_64.sh")
```


# For more info

https://github.com/conda/constructor
https://github.com/conda-incubator/condacolab
