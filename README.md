# Crawl4AI2

Crawl4AI2 is a lightweight API layer that wraps the official Crawl4AI Docker image and exposes a `/api/v1/crawl` endpoint for structured domain scraping. It is designed for use with GPT-based assessment pipelines, including investor and company tech scans.

---

## 🚀 Deployment

This repo uses a minimal Dockerfile that pulls the official image:

```Dockerfile
FROM crawl4ai/crawl4ai:latest
EXPOSE 3000
