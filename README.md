## Contents

- [Project Setup](#project-setup)
- [How To Run The Server](#how-to-run-the-server)
- [Accessing Swagger Docs](#accessing-swagger-docs)

## Project Setup

Be sure to run this in virtual environment:

```shell
python -m venv myvenv
```

then activate it:

```shell
source myvenv/bin/activate
```

## How To Run The Server

Be sure that you have an active virtual environmen and then on your terminal run:

```shell
uvicorn main:app --reload
```

## Accessing Swagger Docs:

While having the server running, access the server url + '/docs'.

* Example:
  - `http://127.0.0.1:8000/docs`
