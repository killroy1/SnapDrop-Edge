# SnapDrop Edge

A simple edge-powered file dropbox using Cloudflare Workers + Pages + R2.

## Features
- Upload files via signed URLs
- Download with expiring links
- Runs entirely at the edge

## Deploy
1. Create an R2 bucket named `snapdrop-edge`.
2. Update `wrangler.toml` with your account details.
3. Deploy Worker:
   ```bash
   cd worker
   wrangler deploy


---

