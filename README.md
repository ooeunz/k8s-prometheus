# k8s-prometheus

> [Prometheus Reference](https://prometheus.io/docs/prometheus/latest/getting_started/)

### How to build this project
```bash
# Create kubernetes namespace -> name is monitoring
kubectl create ns monitoring

# Change Directory
cd k8s-prometheus

# Build kubernetes template
kubectl apply -f .

# Check kubernetes pods of monitoring namespace
kubectl get pod -n monitoring
```

Then you can approch prometheus visual tool.
Enter url like `ip:30003` in your browser like.