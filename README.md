## Monitoring  Database Mysql, PostgreSQL  and Server

# Docker image: 
  - docker pull prom/prometheus

# Storage retation prometheus = 720hs

# Playbook install Grafana


# Backup Dashboard Grafana
   - Create token 
      - url -X POST -H "Content-Type: application/json" -d '{"name":"apikeycurl", "role": "Admin"}' http://admin:password@grafana-infra.exemplo.com.br:3000/api/auth/keys
