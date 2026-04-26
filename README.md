# helm-charts
helm chart learning 

## Run with Docker (Nginx)

Build the image:

```bash
docker build -t helm-charts-nginx .
```

Run it locally:

```bash
docker run --rm -p 8080:80 helm-charts-nginx
```

Then open:

`http://localhost:8080`
