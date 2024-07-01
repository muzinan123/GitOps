# GitOps with Tekton, ArgoCD, and Helm Chart

This repository demonstrates a GitOps workflow using Tekton, ArgoCD, and Helm Chart.

## Prerequisites
- Kubernetes cluster
- Tekton installed on the cluster
- ArgoCD installed on the cluster
- Helm installed locally or on the cluster

## Repository Structure
.
├── .tekton
│   ├── pipelines
│   │   ├── pipeline.yaml
│   ├── tasks
│   │   ├── build-task.yaml
│   │   ├── deploy-task.yaml
├── helm-chart
│   ├── Chart.yaml
│   ├── values.yaml
│   ├── templates
├── argocd
│   ├── application.yaml
└── README.md


