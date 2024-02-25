# SpaceX Past Launches

Quick speed coding project to gain some exposure to Django and Angulars upcoming control flow syntax.

# Dependencies

- node v18.17.0 or later
- python3

# Installation

## Front

### Installation

The front-end has been built for node v18.17.0. To install and run:

```sh
cd spacex-launches-front 
npm i
```

### Running dev server

```sh
npm run start
```

The app can then be accessed on `http://localhost:4200/`

## Server

### Installation

```sh
cd spacex-launches-server
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

### Running dev server

```sh
python3 manage.py runserver
```

The API will then be exposed on port 8000; give this endpoint a try to check that it is working:

`http://localhost:8000/api/v1/launches/past`
