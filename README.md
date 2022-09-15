
Secret for github webhook:

```
kubectl -n argo-events \
  create secret generic event-ecommercedemo-astro-solidjs-github-secret \
  --dry-run=client \
  --from-literal secret="HF8kJqc96N3xcj" \
  --output yaml | kubeseal -o yaml
```
