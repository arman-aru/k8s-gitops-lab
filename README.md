# k8s-gitops-lab

> Kubernetes + GitOps lab — k3s, Helm charts and Argo CD deploying my Python and Go services, with Prometheus and Grafana monitoring.

![status](https://img.shields.io/badge/status-in%20progress-yellow) ![area](https://img.shields.io/badge/area-DevOps-blue) ![license](https://img.shields.io/badge/license-MIT-green)

🚧 **Work in progress.** This repo is part of my public learning roadmap (**Phase 2 — DevOps**). I build in the open — follow the commits and the roadmap below.

## Why this project

Run real services the way production teams do: declarative, versioned in Git, and observable.

## What I'm learning

- Kubernetes core objects: Deployments, Services, Ingress, ConfigMaps, Secrets
- Packaging apps with Helm
- GitOps with Argo CD
- Monitoring with Prometheus and Grafana
- Zero-downtime rollouts and rollbacks

## Planned stack

k3s · Helm · Argo CD · ingress-nginx · cert-manager · Prometheus · Grafana

## Roadmap

- [ ] Local cluster with k3d/kind + bootstrap script
- [ ] Helm chart for `lt-vocab-api` (with PostgreSQL)
- [ ] Helm chart for `parcel-locker-api`
- [ ] Argo CD app-of-apps setup
- [ ] Ingress + TLS with cert-manager
- [ ] Prometheus + Grafana, scraping `go-uptime` metrics
- [ ] Rolling update + rollback demo
- [ ] README: architecture diagram and runbook

## Part of a 10-repo learning roadmap

I'm a full-stack developer in Vilnius ([armansalek.com](https://armansalek.com)) growing into **Python, Go, DevOps, cloud and AI engineering**. These repos connect: the Python and Go services are containerised, deployed and monitored by the DevOps and cloud repos, and the AI projects run on that infrastructure.

| # | Repo | Area | Phase |
|---|---|---|---|
| 1 | [lt-jobs-scraper](https://github.com/arman-aru/lt-jobs-scraper) | Python | 1 |
| 2 | [lt-vocab-api](https://github.com/arman-aru/lt-vocab-api) | Python | 1 |
| 3 | [parcel-locker-api](https://github.com/arman-aru/parcel-locker-api) | Golang | 1 |
| 4 | [go-uptime](https://github.com/arman-aru/go-uptime) | Golang | 1 |
| 5 | [ci-cd-pipelines](https://github.com/arman-aru/ci-cd-pipelines) | DevOps | 2 |
| 6 | **k8s-gitops-lab** (this repo) | DevOps | 2 |
| 7 | [terraform-aws-platform](https://github.com/arman-aru/terraform-aws-platform) | Cloud Computing | 3 |
| 8 | [serverless-media-pipeline](https://github.com/arman-aru/serverless-media-pipeline) | Cloud Computing | 3 |
| 9 | [site-audit-agent](https://github.com/arman-aru/site-audit-agent) | AI Engineering | 4 |
| 10 | [migration-rag-assistant](https://github.com/arman-aru/migration-rag-assistant) | AI Engineering | 4 |

## License

[MIT](LICENSE) © Arman Salek
