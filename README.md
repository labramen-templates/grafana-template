# grafana-template

LabRamen template for Grafana OSS on Ubuntu 24.04 LXC.

Deploys a clean Grafana instance on port 3000 with admin credentials set to your LabRamen container user. No pre-configured dashboards or datasources — a blank slate ready for your monitoring setup.

## Defaults

| Resource | Default |
|----------|---------|
| CPU | 2 cores |
| Memory | 2048 MB |
| Disk | 12 GB |
| OS | Ubuntu 24.04 |
| Grafana Port | 3000 |

## Authentication

Grafana admin credentials are set to `container_user_name` / `container_user_password` from your LabRamen config.
