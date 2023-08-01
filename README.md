## Contents

- [Project Setup](#project-setup)
- [How To Run The Server](#how-to-run-the-server)
- [Accessing Swagger Docs](#accessing-swagger-docs)
- [Postman](#postman)

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

## Accessing Swagger Docs

While having the server running, access the server url + '/docs'.

* Example:
  - `http://127.0.0.1:8000/docs`

## Postman

### Importing The Postman Collection

There are two files inside the `/postman` folder.

The one named `./postman/FAST API TUTORIAL.postman_collection.json` is the collection. To import it click on
`import` on the top left corner of you postman, then click file and then `import`.

![alt text](https://github.com/EduardoBorsa/fastapi_tutorial/blob/main/static/postman_import_tut_01.png)

### Importing The Postman Environment

The other file is named `./postman/Fast API User Guide.postman_environment.json` is the environment. To import it click on
`import` on the top left corner of you postman, then click file and then `import`. The environment will appear on the top right
corner. You have to choose the environment.

![alt text](https://github.com/EduardoBorsa/fastapi_tutorial/blob/main/static/postman_import_tut_02.png)
