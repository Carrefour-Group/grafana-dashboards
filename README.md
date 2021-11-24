# grafana-dashboards

## [`kube-bench`](./kube-bench-dashboard.json)

Shows [`aquasec/kube-bench`](https://github.com/aquasec/kube-bench) outputs from Loki logs.

## [`node-exporter-nfs`](./node-exporter-nfs-dashboard.json)

Shows [`prometheus/node_exporter`](https://github.com/prometheus/node_exporter) `mountstats` NFS metrics.
`mountstats` collector should be enabled in the `node_exporter` configuration.
