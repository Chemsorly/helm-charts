# Helm Charts

Helm chart repository for [Chemsorly](https://github.com/Chemsorly) projects.

## Usage

```bash
helm repo add chemsorly https://chemsorly.github.io/helm-charts
helm repo update
```

## Available Charts

| Chart | Description |
|-------|-------------|
| [coding-agent-automation](./charts/coding-agent-automation/) | Multi-agent coding automation platform |

## Publishing

Charts are published automatically via [chart-releaser-action](https://github.com/helm/chart-releaser-action).
When chart source is pushed to `charts/<name>/` on `main`, the workflow packages the chart,
creates a GitHub Release, and updates the Helm repository index on the `gh-pages` branch.
