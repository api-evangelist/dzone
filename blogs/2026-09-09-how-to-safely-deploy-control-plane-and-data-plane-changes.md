---
title: "How to Safely Deploy Control-Plane and Data-Plane Changes With Argo CD and Argo Rollouts"
url: "https://dzone.com/articles/argocd-safe-deploy"
date: "2026-09-09"
author: "Akhil Madineni"
feed_url: "https://feeds.dzone.com/home"
---
Deployments become harder when one release changes both the machinery governing a Kubernetes platform and the workloads that depend on it. A new CustomResourceDefinition, admission webhook, controller, or routing API can change what the cluster accepts and how it behaves; a new application image can simultaneously depend on those changes. Argo CD and Argo Rollouts solve different parts of this problem.
