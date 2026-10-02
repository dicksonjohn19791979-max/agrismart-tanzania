# AgriSmart Tanzania

AI-Powered Smart Agriculture Management & Advisory System frontend.

## Deployment

This project is a standalone static HTML/CSS/JavaScript frontend.

### GitHub

```bash
git init
git add .
git commit -m "Initial AgriSmart Tanzania frontend"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/agrismart-tanzania.git
git push -u origin main
```

### Render

Create a **Static Site** connected to the GitHub repository.

- Build Command: leave empty
- Publish Directory: `.`
- Auto-Deploy: Yes

The included `render.yaml` can also be used with Render Blueprint deployment.

## Important

The current version is a frontend/demo implementation. It does not yet connect to a backend API or database. Login is demo-only, and actions such as SMS/IVR broadcast are simulated in the browser.

For production use, connect authentication, farmer records, weather, market data, AI/ML services, SMS/IVR, and database persistence through a secure backend API. Do not put API secrets in `index.html`.
