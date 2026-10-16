# k8s-gitops-lab

> Kubernetes + GitOps lab — k3s, Helm charts and Argo CD deploying my Python and Go services, with Prometheus and Grafana monitoring.

![status](https://img.shields.io/badge/status-in%20development-yellow) ![license](https://img.shields.io/badge/license-MIT-green)

## Overview

A Kubernetes setup managed entirely through Git. Helm charts and Argo CD deploy Python and Go services to a k3s cluster, with TLS, monitoring and safe rollouts.

## Features

- Local k3s cluster bootstrapped with one script
- Helm charts for each service and its database
- GitOps deployments with Argo CD (app-of-apps)
- Ingress with automatic TLS via cert-manager
- Prometheus + Grafana monitoring
- Rolling updates and one-command rollbacks

## Tech stack

k3s · Helm · Argo CD · ingress-nginx · cert-manager · Prometheus · Grafana

## License

[MIT](LICENSE) © Arman Salek
