# djangular-pack
A start pack for django with angular 5

## Requirement
- Python3
- pip
- nodejs
- virtualenv

## Setup

### Create a virtual environment
```
$ virtualenv ~/.virtualenvs/[your-venv-name]/ -p python3
```

### Activate virtual environment
```
$ source ~/.virtualenvs/[you-venv-name]/bin/activate
```

### Install dependencies
```
$ pip install -r requirements.txt
$ pip install --upgrade git+git://github.com/syrusakbary/pyjade.git@d8cf1d9404c759c6a2430c9a900874ab
0e970cd8
$ cd ./angular-client/
$ yarn (or npm i)
```

### Set the port number at which django dev server will run
```
$ cd ../
$ echo [port number] > port
```

### Migrate database
```
$ ./manage.py migrate
```

## Commands

### django server
```
$ yarn run django (or npm run django)
```

## Lints

### django-lint
```
$ yarn run lint:djg (or npm run lint:djg)
```
