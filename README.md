# Hello Wissen

A simple static HTML application displaying a friendly message.

## Quick Start

### Local
Open `index.html` in any modern web browser.

### Docker
```bash
docker build -t hello-wissen .
docker run -d -p 8080:80 hello-wissen
```
Then visit http://localhost:8080.

## Tech Stack
- Plain HTML5, CSS, JavaScript
- Served via Nginx (Docker) or any static file server

## ADR
See [ADR-001](adr/ADR-001.md) for architecture decisions. (Not yet created)
