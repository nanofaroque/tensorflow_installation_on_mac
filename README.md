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

### 4. Install tensorflow
``` conda install tensorflow```
