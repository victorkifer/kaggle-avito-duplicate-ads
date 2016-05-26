# Prepare Environment

```
apt-get install python-virtualenv
```

In project directory

```
virtualenv -p python3 ./ # creates virtual env
source bin/activate # go to virtual env

pip -r dependencies.txt # install dependencies
```

To start working

```
source bin/activate # go to virtual env
jupyter notebook
```