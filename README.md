# App1 – Kubernetes Basics Lab

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white) ![Apache](https://img.shields.io/badge/Apache_httpd-D22128?logo=apache&logoColor=white)

> Kubernetes Pod and Deployment manifests for a first hands-on lab.

## Overview

Introductory Kubernetes lab: a single **Pod** running Apache httpd and a **Deployment** that scales a web server to 5 replicas.

## Tech Stack

- **Kubernetes**
- **Apache httpd**

## Repository Structure

```text
deployment-test.yml
pod-lab1.yml
README.md
```

## Getting Started

```bash
git clone https://github.com/Gamal-Mohammad/app1.git
cd app1
```

### Deploy to Kubernetes

| File | Kind | Name |
|---|---|---|
| `deployment-test.yml` | Deployment | `test` |
| `pod-lab1.yml` | Pod | `lab1` |

```bash
kubectl apply -f deployment-test.yml
kubectl apply -f pod-lab1.yml
kubectl get pods,svc
```

## Author

**Gamal Mohammad**

[![GitHub](https://img.shields.io/badge/GitHub-Gamal--Mohammad-181717?logo=github)](https://github.com/Gamal-Mohammad)
