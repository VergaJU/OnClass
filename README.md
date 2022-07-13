# OnClass
 OnClass repo to work with my datasets, the main reason to create this repo is to ensure a version with all compatible libraries that can be portable and works in different machines.

## env

Create conda env using the file [OnClass_env.yml](env/OnClass_env.yml):

```
conda env create -f OnClass_env.yml
conda activate OnClass
```
Conda doesn't manage to install correctly all the python packages, to ensure all the packages are installed in the correct version, install them using the file [requirements.txt](env/requirements.txt):

```
pip install -r requirements
```

TODO: Container to run it in any machine
