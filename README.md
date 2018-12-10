# Prometheus 

Visualization of Prometheus [rules](https://prometheus.io/docs/prometheus/latest/querying/api/#rules) and [alerts](https://prometheus.io/docs/prometheus/latest/querying/api/#alerts) API. 

# Basic idea

Alerting of grafana is somewhat limited, I prefer prometheus and alertmanager personally. However, alert rules of prometheus cannot be visualized like grafana alert rule, nor can we manage the alert rules from GUI. 

[Alertmanager Datasource](https://github.com/camptocamp/grafana-prometheus-alertmanager-datasource) introduce alertmanager to grafana, which inspired me to integrate the visualization of alert rules into grafana dashboards. 
