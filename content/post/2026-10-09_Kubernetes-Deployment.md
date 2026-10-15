First Kubernetes Deployment

---

title: "First Kubernetes Deployment"
date: 2026-10-09
tags: ["kubernetes", "code"]

First application on Kubernetes using Kubernetes deployments.

<!--more-->kubectl run kubernetes-bootcamp --image=gcr.io/google-samples/kubernetes-bootcamp:v1 --port=8080

Now, check whether it is running:

kubectl get pods

We can check application logs:

kubectl logs kubernetes-bootcamp
