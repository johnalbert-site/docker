# My First Website

A simple static website deployed with GitHub Pages and Docker.

## Run with Docker

```bash
docker build -t my-website .
docker run -d -p 8080:80 my-website
```

Then open http://localhost:8080
