# Docker-Servidores

Repositório para configuração e gerenciamento de múltiplos serviços utilizando **Docker Compose**. Este projeto facilita a implementação e execução de servidores locais ou em ambiente de desenvolvimento.

## Serviços Incluídos

1. **Elasticsearch-Kibana**  
   Monitoramento e busca de dados.
2. **Jenkins**  
   Servidor de automação para CI/CD.
3. **Nextcloud-Postgres**  
   Plataforma de armazenamento em nuvem privada.
4. **Portus**  
   Registro privado de imagens Docker.
5. **Prometheus-Grafana**  
   Monitoramento de métricas e dashboards.
6. **Redis**  
   Banco de dados em memória.
7. **SonarQube**  
   Análise contínua de qualidade de código.
8. **SQL Server**  
   Banco de dados relacional SQL Server.
9. **Zookeeper-Kafka-CMAK**  
   Mensageria distribuída com Apache Kafka e ZooKeeper.

---

## Requisitos

- **Docker** (>= 20.x)
- **Docker Compose** (>= 2.x)

---

## Como Utilizar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/docker-servidores.git
   cd docker-servidores

1. Rodar os projectos no docker:
  ```bash
  docker-compose up -d

