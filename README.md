## Install a gitlab runner instance in minikube

```
helm repo add gitlab https://charts.gitlab.io
helm install gitlab-runner gitlab/gitlab-runner -f values-%1.yaml
```
