# practice-fastapi

Use fastapi Python library as a try

```sh
python -m venv .venv
source .venv/bin/activate

pip install "fastapi[standard]" # if not installed
fastapi dev main.py # ^C to quit

deactivate
```

```sh
source .venv/bin/activate
fastapi dev main.py

curl -H "Content-Type: application/json" localhost:8000/?name=Steve
# {"message":"Hello, Steve!"}
```
