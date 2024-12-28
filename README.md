# GitHub Pages Deployment

This repository is configured to automatically deploy static content to GitHub Pages from the `docs/dist` directory.

## Deployment Configuration

The deployment is handled through GitHub Actions workflow that:
- Triggers on pushes to the `master` branch
- Deploys content from the `docs/dist` directory
- Automatically publishes to GitHub Pages

## Directory Structure

```
.
└── docs/
    └── dist/     # Static content to be deployed
```

## Manual Deployment

You can also trigger the deployment manually from the Actions tab in the GitHub repository.
