# Kubectl Course

Hands-on repo for learning kubectl basics and daily workflows.

## What You'll Learn
- Core kubectl commands for inspecting and managing Kubernetes resources
- Common flags and output formats (`-o wide`, `-o yaml`, `--watch`)
- Safe edit/update patterns and dry runs
- Simple resource create/delete/apply cycles

## Prerequisites
- Access to a Kubernetes cluster (local or remote)
- `kubectl` installed and pointing to the target context

## How to Use
1) Make sure your kubeconfig is set to the right cluster/context.
2) Work through the examples and notes in this repo, running the commands as you go.
3) Use `kubectl explain <resource>` and `kubectl get <resource> -o yaml` to deepen understanding.

## Helpful Commands
- `kubectl config get-contexts` – list contexts
- `kubectl get pods -A` – quick cluster check
- `kubectl apply -f <file>` – apply manifests from this repo
- `kubectl delete -f <file>` – clean up when done
