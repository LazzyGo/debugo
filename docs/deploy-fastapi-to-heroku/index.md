# Deploy Fastapi to Heroku

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

