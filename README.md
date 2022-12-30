# Codefresh GitOps Certification examples - Level 2 - GitOps at scale

This repository contains examples for the ArgoCD/GitOps
certification workshops (Level 2)

Take the certification yourself at https://codefresh.io/courses/get-gitops-certified/


create
```
argocd app create example06 --project default --sync-policy auto --repo https://github.com/paul-nguyen-setel/gitops-cert-level-2-examples --path ./sync-hooks-waves/06-waves-and-hooks --dest-server https://kubernetes.default.svc --dest-namespace example06

```