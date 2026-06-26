# k8s-homelab

A two-node Proxmox cluster running Kubernetes on TalosOS. Managed through GitOps via ArgoCD — mostly a way to learn by breaking things in an environment where that's acceptable.

Running since February 2026. Fresh repo because the original commit history was a bit too honest about the learning process.

## Stack

- **OS:** TalosOS
- **Hypervisor:** Proxmox (2-node cluster)
- **GitOps:** ArgoCD (app-of-apps pattern)
- **Ingress:** Traefik
- **Storage:** Longhorn
- **Observability:** Prometheus, Loki, Promtail
- **Secrets:** Sealed Secrets
- **Network access:** Twingate
- **DNS:** Cloudflare DDNS, cert-manager for TLS
