# tensorflow_installation_on_mac
Installing tensorflow on MAC even if you have python 3.7

## Steps to run tensorflow on mac
### 1. Install miniconda on mac
download  Miniconda (bash installer) from

https://docs.conda.io/en/latest/miniconda.html 

```cd Downloads```

```bash Miniconda3-latest-MacOSX-x86_64.sh```

### 2. Add to your rc or bash_profile
``` export PATH="/Users/my-user-name/miniconda3/bin:$PATH" ```

### 3. Create a env by using conda
``` conda create --name vrf python=3.6 ```

### 4. Activate new env

```source activate venv```

### 5. Install tensorflow
``` conda install tensorflow```

### 6. check all the installation
```pip freeze```

This command show something like this: 

absl-py==0.7.1

astor==0.8.0

certifi==2019.6.16

gast==0.2.2

grpcio==1.16.1

h5py==2.9.0

Keras-Applications==1.0.8

Keras-Preprocessing==1.1.0

Markdown==3.1.1

mkl-fft==1.0.14

mkl-random==1.0.2

mkl-service==2.0.2

numpy==1.16.4

protobuf==3.8.0

scipy==1.3.1

six==1.12.0

tensorboard==1.14.0

tensorflow==1.14.0

tensorflow-estimator==1.14.0

termcolor==1.1.0

Werkzeug==0.15.5

wrapt==1.11.2
