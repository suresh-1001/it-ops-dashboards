# Monitoring Quick Start
## Node Exporter
docker run -d --name node_exporter -p 9100:9100 prom/node-exporter
## Prometheus
docker run -d --name prom -p 9090:9090 -v $PWD/prometheus.yml:/etc/prometheus/prometheus.yml prom/prometheus
## Grafana
docker run -d --name grafana -p 3000:3000 grafana/grafana
# Import grafana_dashboard.json via Grafana -> Dashboards -> Import


## Artifacts
- `/docs/` step-by-step with screenshots
- `/scripts/` repeatable automation
- `/dashboards/` sample JSON/PBIX (if relevant)
- `/templates/` redacted policies/SOPs

---
**Contact**  
- Email: **suresh@echand.com**  
- LinkedIn: **linkedin.com/in/sureshchand01**
