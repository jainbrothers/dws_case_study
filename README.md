# FastAPI Hello World

A minimal FastAPI application that returns a Hello World JSON response.

## Setup

```bash
# Create and activate a virtual environment
python -m venv .venv

# Windows
.venv\Scripts\activate

# macOS / Linux
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Install dev dependencies (includes test tools)
pip install -r requirements-dev.txt
```

## Run the app

```bash
python -m uvicorn app.main:app --reload
```

The API will be available at [http://127.0.0.1:8000](http://127.0.0.1:8000).

### Endpoints

| Method | Path | Description |
|--------|------|-------------|
| GET    | `/`  | Returns `{"message": "Hello World"}` |

## Run the tests

```bash
python -m pytest
```
