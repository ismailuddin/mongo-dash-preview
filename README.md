# Mongo Dash preview
Repository for deploying Mongo Dash on Heroku for a live preview.

## Usage
First install the requirements:

```shell
$   pip install -r requirements.txt
```

Next, launch the server:

```shell
$   gunicorn main:app -w 1 -k uvicorn.workers.UvicornWorker
```
