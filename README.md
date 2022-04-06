# flask-app

## Docker

- `docker build -t flask-test .`
- `docker run -dp 5000:5000 flask-test`

## Dev Server

- Start server: `flask run`
- Stop server: `<kbd>Ctrl</kbd> c`

## Waitress Server

- `waitress-serve --call 'flaskr:create_app'`

## Network Troubleshooting

- Check running containers: `docker ps`
- Check ports: `lsof -i tcp:5000`
