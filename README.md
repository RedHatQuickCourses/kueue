# GPU Quota Management with Kueue on Red Hat OpenShift AI

Antora-based course teaching GPU quota management using Kueue on OpenShift with the Fake GPU Operator.

Published at: https://redhatquickcourses.github.io/kueue

## Local Development

### Prerequisites

- Node.js 22+
- npm

### Build and Preview

```bash
# Install dependencies
npm install

# Build the site
npm run build

# Serve locally (http://localhost:8080)
npm run serve

# Auto-rebuild on changes (run in a separate terminal from serve)
npm run watch:adoc
```

### Output

Generated HTML is written to `build/site/`.

## Publishing

Push to `main` branch. GitHub Actions builds and deploys to GitHub Pages automatically.

Pull requests get preview deployments at `/pr-<number>/`.
