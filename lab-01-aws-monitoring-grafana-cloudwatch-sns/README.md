---

# 📊 Monitoramento e Observabilidade com Grafana

Como parte desta arquitetura, foi implementado um sistema completo de observabilidade utilizando o Grafana integrado ao Amazon CloudWatch.

Isso permite monitorar em tempo real todos os recursos da infraestrutura, incluindo:

- Amazon EC2 (CPU, Network, Status checks)
- Auto Scaling Group (Desired capacity, instances)
- Application Load Balancer
- Amazon RDS (Latency, IOPS, Connections)
- Amazon CloudFront (Requests, Error rates, Traffic)
- AWS Certificate Manager (expiração de certificados)

## 📷 Evidências do Grafana

### Monitoramento EC2

![Grafana EC2](evidencias/grafana-ec2.png)

### Monitoramento CloudFront

![Grafana CloudFront](evidencias/grafana-cloudfront.png)

### Monitoramento Auto Scaling

![Grafana Auto Scaling](evidencias/grafana-asg.png)

### Monitoramento RDS

![Grafana RDS](evidencias/grafana-rds.png)

### Monitoramento ACM

![Grafana ACM](evidencias/grafana-acm.png)

---

## 🎯 Benefícios desta implementação

- Observabilidade completa da infraestrutura
- Monitoramento em tempo real
- Identificação rápida de falhas
- Visualização centralizada de métricas
- Arquitetura alinhada com AWS Well-Architected Framework

---


## 👨‍💻 Autor

George Luís dos Santos  
AWS Cloud | DevOps | Solutions Architect (em formação)
