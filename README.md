# Ariadne Starlette Microservice Template

## Build

```bash
docker build . --tag ariadne-starlette-microservice:latest
```

## Run

### Development

```bash
uvicorn --app-dir app --port 3000 --reload main:app
```

### Production

```bash
docker run -d -p 3000:3000 ariadne-starlette-microservice:latest
```