# [FastAPI](https://fastapi.tiangolo.com/) ([ja](https://fastapi.tiangolo.com/ja/)) のインストール

```
pip install fastapi
```

※[Uvicorn](https://www.uvicorn.org/)または[Hypercorn](https://gitlab.com/pgjones/hypercorn)をインストールする
```
pip install uvicorn
```

--------
#### Create a file `main.py`

```
from fastapi import FastAPI

app = FastAPI()


@app.get("/")
def read_root():
    return {"Hello": "World"}
```

#### Run the server
```
uvicorn main:app --reload
```

Interactive API docs (provided by Swagger UI):
  http://127.0.0.1:8000/docs

Alternative API docs (provided by ReDoc):
  http://127.0.0.1:8000/redoc
