# KUBECTL COMMANDS TO GET STARTED

How to restart a deployment and load new image.
```yaml
kubectl rollout restart deploy/react-server
```

How to stream logs from a deployment container.
```yaml
kubectl logs -f -lapp=react-server --all-containers=true
```