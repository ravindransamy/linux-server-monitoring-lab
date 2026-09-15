Linux Server Monitoring Lab

Technologies:
- Ubuntu
- Zabbix 7.0
- Grafana
- Docker
- Docker Compose
- Zabbix Agent
- Windows Server 2019

Monitoring:
- CPU utilization
- Memory utilization
- Disk usage
- Network traffic
- System uptime
- Windows Server monitoring
- Linux Server monitoring
- Service monitoring

Alert Testing:
- High CPU utilization
- Zabbix Agent unavailable
- Problem and recovery verification

Architecture:
Linux Server
    |
    +-- Zabbix Server
    +-- Zabbix Web
    +-- PostgreSQL
    +-- Grafana
    |
    +-- Windows Server 2019
          |
          +-- Zabbix Agent
