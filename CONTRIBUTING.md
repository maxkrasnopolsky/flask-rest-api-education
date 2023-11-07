# CONTRIBUTING

## How to run the Dockerfile locally

```angular2html
docker run -dp 5005:5000 -w /app -v "$(pwd):/app" flask-api sh -c "flask run --host 0.0.0.0"
```