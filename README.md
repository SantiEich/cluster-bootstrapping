# ArgoCD Example Apps

```
argocd app create cluster-bootstrap --repo https://github.com/santieich/cluster-bootstrapping --path cluster-bootstrap --dest-namespace default --dest-server https://kubernetes.default.svc --helm-set github_token=$(echo $GITHUB_TOKEN | base64)

```