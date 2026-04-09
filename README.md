# Alpaca Paper Trading Kubernetes Manifests

This repository contains the Kustomize-based Kubernetes manifests for the Alpaca paper trading platform.

Structure:
- `base/` — base manifests and Kustomize resources.
- `kustomization.yaml` — top-level Kustomize entry.

Apply with:
```bash
kubectl apply -k .
```
