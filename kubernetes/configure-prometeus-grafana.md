# Prometheus and Grafana

## Steps to configure Prometheus

```
helm search hub Prometheus
```

```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
```

```
helm install prometheus prometheus-community/prometheus --version 27.8.0
```

## Steps to configure Grafana

```
helm search hub Grafana
```

```
helm repo add prometheus https://grafana.github.io/helm-charts
```

```
helm install my-grafana grafana/grafana --version 8.12.0
```
