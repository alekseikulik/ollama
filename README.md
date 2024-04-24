# Ollama LLM

This project contain files to deploy Ollama and WebUI

## TLDR

Helmfile configured by default to deploy the bundle to your local Kubernetes cluster.

```bash
# Start local Kubernetes cluster
clima kubernetes start

# Deploy the bundle. Add "-i" to enable interactive mode
helmfile apply

```

## Cleanup

```bash
# Uninstal the bundle
helmfile destroy
```
