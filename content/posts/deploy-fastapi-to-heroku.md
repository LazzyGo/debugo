---
title: "Deploy Fastapi to Heroku"
date: 2022-03-07T07:14:16Z
tags: ["heroku","fastapi"]
categories: ["python"]
---
run.py


```python
from fastapi import FastAPI

app = FastAPI()

@app.get("/")
async def root():
    return {"message": "Hello World"}
```

Procfile
```
web: gunicorn -w 4 -k uvicorn.workers.UvicornWorker run:app
```

requirements.txt
```
fastapi
gunicorn
uvicorn
```
