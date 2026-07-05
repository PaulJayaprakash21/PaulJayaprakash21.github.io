# Paul Gomez — Portfolio

Personal portfolio site: production support & middleware engineer (IBM WebSphere, IBM MQ) building toward Azure cloud engineering.

**Live site:** https://pauljayaprakash21.github.io

## Stack

Plain HTML and CSS, no frameworks, no build step. Hosted free on GitHub Pages.

## Structure

```
.
├── index.html    # the entire site (styles embedded)
└── README.md
```

## Deploying (GitHub Pages)

1. Rename the repository to exactly `PaulJayaprakash21.github.io` (Settings → Repository name).
2. Push this code:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/PaulJayaprakash21/PaulJayaprakash21.github.io.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages → Source: Deploy from a branch → main / (root)**.
4. The site goes live at `https://pauljayaprakash21.github.io` within a couple of minutes.

## Related lab repos

The Azure lab projects linked from the site live in their own repositories:

- `azure-acr-fastapi` — FastAPI app containerized and pushed to Azure Container Registry
- `azure-aks-lab` — AKS cluster setup and workload deployment notes
- `azure-traffic-manager-lab` — multi-region routing across Australia East / Canada East
- `azure-service-bus-lab` — Service Bus queues & topics, compared against IBM MQ
- `azure-iac-lab` — Terraform and ARM templates via Azure DevOps

## Updating content

All contact details are baked into `index.html`. No placeholders remain.

Everything is in `index.html`. Placeholders to replace before going live:


