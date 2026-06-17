# Check-In App

Static QR-based check-in client for on-site verification.

## What It Does
- Scan/verify participant QR
- Manual registration ID verification
- Check-in marking
- Basic check-in stats and recent activity

## Setup
1. Open `index.html` and set backend URL.
2. Serve via HTTP (not `file://`).

## Local Run
```bash
python -m http.server 8080
```
Then open:
- `http://localhost:8080/index.html`

## Backend Requirements
Expected endpoints:
- `POST /api/checkin/verify`
- `POST /api/checkin/checkin`
- `GET /api/checkin/stats`

## Deploy
Deploy as static site (Cloudflare Pages / Vercel / Netlify).

## Notes
- Camera permission is required for QR scanning.
- Ensure backend CORS includes deployed check-in URL.
"# checkin-demo" 
"# checkin-demo" 
"# checkin-demo" 
