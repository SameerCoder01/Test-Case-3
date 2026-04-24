# Node.js API

Simple Express REST API with a health check endpoint.

## Run locally

1. Install dependencies:

```bash
npm install
```

2. Start the server:

```bash
npm start
```

3. Open `http://localhost:8080/health`

Expected response:

```json
{ "status": "OK" }
```
