# 📊 Lab 01 – AWS Monitoring and Observability with Grafana, CloudWatch and SNS

Este laboratório demonstra a implementação de um sistema completo de **monitoramento e observabilidade na AWS**, utilizando o **Grafana integrado ao Amazon CloudWatch**, permitindo a visualização centralizada de métricas e monitoramento em tempo real de toda a infraestrutura.

Este projeto segue as boas práticas do **AWS Well-Architected Framework**, com foco em observabilidade, confiabilidade e operação eficiente.

---

# 🎯 Objetivo

Implementar uma solução de observabilidade capaz de monitorar recursos críticos da infraestrutura AWS, permitindo:

- Monitoramento em tempo real
- Visualização centralizada de métricas
- Identificação rápida de falhas
- Análise de performance e disponibilidade
- Suporte a arquiteturas altamente disponíveis

---

# 🏗️ Arquitetura de Monitoramento

Fluxo da observabilidade:

AWS Resources  
→ Amazon CloudWatch (coleta de métricas)  
→ Grafana (visualização e dashboards)  
→ Amazon SNS (alertas e notificações)

---

# ⚙️ Recursos monitorados

Este laboratório monitora os seguintes serviços AWS:

- Amazon EC2  
  - CPU Utilization  
  - Network In / Out  
  - Status Checks  

- Auto Scaling Group  
  - Desired Capacity  
  - Instances in Service  
  - Scaling events  

- Application Load Balancer  
  - Request Count  
  - Latency  
  - Healthy Hosts  

- Amazon RDS  
  - Read / Write Latency  
  - IOPS  
  - Database Connections  

- Amazon CloudFront  
  - Requests  
  - Error Rates (4xx / 5xx)  
  - Traffic volume  

- AWS Certificate Manager (ACM)  
  - Monitoramento de expiração de certificados SSL/TLS  

---

# 📷 Evidências do Grafana

## Monitoramento EC2

![Grafana EC2](evidencias/grafana-ec2.png)

---

## Monitoramento CloudFront

![Grafana CloudFront](evidencias/grafana-cloudfront.png)

---

## Monitoramento Auto Scaling

![Grafana Auto Scaling](evidencias/grafana-asg.png)

---

## Monitoramento RDS

![Grafana RDS](evidencias/grafana-rds.png)

---

## Monitoramento ACM

![Grafana ACM](evidencias/grafana-acm.png)

---

# 🚨 Alertas e notificações

O Amazon CloudWatch foi integrado ao Amazon SNS para envio de notificações automáticas em caso de:

- Falha de instâncias
- Eventos de Auto Scaling
- Problemas de infraestrutura
- Alterações críticas de performance

---

# ✅ Benefícios da solução

- Observabilidade completa da infraestrutura AWS  
- Monitoramento centralizado com Grafana  
- Integração com Amazon CloudWatch  
- Alertas automáticos com Amazon SNS  
- Arquitetura resiliente e pronta para produção  
- Aderente ao AWS Well-Architected Framework  

---

# 🧠 Tecnologias utilizadas

- Amazon CloudWatch  
- Amazon SNS  
- Grafana  
- Amazon EC2  
- Auto Scaling Group  
- Application Load Balancer  
- Amazon RDS  
- Amazon CloudFront  
- AWS Certificate Manager  

---

# 🔗 Projeto relacionado

Este monitoramento foi implementado sobre a arquitetura altamente disponível do laboratório:

https://github.com/George-lsantos/Laboratorios-Cloud-AWS/tree/main/lab-16-aws-wordpress-ha-efs-rds

---

# 👨‍💻 Autor

George Luís dos Santos.  

AWS Cloud | DevOps | Observability | Solutions Architect (em formação)

---

# ⭐ Objetivo do laboratório

Projeto desenvolvido como parte da preparação para a certificação:

**AWS Solutions Architect Professional (SAP-C02)**
