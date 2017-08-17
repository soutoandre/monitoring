## Monitoring with Grafana and Prometheus Database Mysql, PostgreSQL  and Server

# Docker image: 
  - docker pull prom/prometheus

# Storage retation prometheus = 720hs

# Backup Dashboard Grafana
   - Create token to grafcli
      - curl -X POST -H "Content-Type: application/json" -d '{"name":"apikeycurl", "role": "Admin"}' http://admin:password@grafana-infra.exemplo.com.br:3000/api/auth/keys


# Dashboard
![Grafana dash](https://github.com/soutoandre/monitoring/blob/master/pgsql.overview.PNG)
