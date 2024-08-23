# Hello Harbor

A small **Go HTTP server** using only the standard library: static files, a hello route, and a form POST handler.

## Features

- Serves `./static`
- `GET /hello`
- `POST /form` (name + address)

## Tech

Go · net/http

## Run

```bash
git clone https://github.com/d28035203/hello-harbor.git
cd hello-harbor
go run .
# http://localhost:8080
```

## License

MIT
