# ClassHello

A simple FastAPI project with hello endpoints.

## Features

- Root endpoint with optional name parameter
- Path endpoint for greeting specific names
- FastAPI framework with automatic API documentation

## Installation

1. Clone the repository:
```bash
git clone https://github.com/coolyuoo/ClassHello.git
cd ClassHello
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Run the application:
```bash
python main.py
```

The API will be available at `http://localhost:8000`

## API Endpoints

- `GET /` - Root endpoint with optional `name` query parameter
- `GET /hello/{name}` - Greet a specific name

## API Documentation

Once the server is running, visit:
- Swagger UI: `http://localhost:8000/docs`
- ReDoc: `http://localhost:8000/redoc`