# nodejs-api

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

3. Or run in development mode with automatic reload:

```bash
npm run dev
```

4. Open the health endpoint in your browser or via curl:

```bash
http://localhost:3000/health
```

Expected response:

```json
{ "status": "OK" }
```

## Notes

- The server listens on `PORT` environment variable or defaults to `8080`.
- To use a different port in PowerShell:

```powershell
$env:PORT=3000
npm start
```
