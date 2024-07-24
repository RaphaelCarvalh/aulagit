<div align="center">

# [Arquitetura AWS de um Site de Ecommerce](https://raphaelcarvalh.github.io/DashBoard-/#/dashboard/)

![SQL Arquitetura ](https://lh3.googleusercontent.com/d/17RzXznYTxAC-ymmSIS1auM3931tcQSyz)
</div>

###

<div align="center">
  <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo"  />
  <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="youtube logo"  />
  <img src="https://img.shields.io/static/v1?message=Twitter&logo=twitter&label=&color=1DA1F2&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="twitter logo"  />
</div>

###

<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=maurodesouza.maurodesouza&"  />
</div>

<h3 align="left">🛠 Ferramentas </h3>

<div align="left">

  ### Amazon EC2 (Elastic Compute Cloud)

- **Instâncias EC2**:
  - Tipo: t2.micro
  - Número de instâncias: 2
  - Região: us-east-1
  - SO: Amazon Linux

### Amazon RDS (Relational Database Service)

- **Banco de Dados**:
  - Tipo: MySQL
  - Versão: 5.7
  - Capacidade: db.t2.micro
  - Região: us-east-1

### Amazon S3 (Simple Storage Service)

- **Armazenamento**:
  - Buckets:
    - Nome: my-app-bucket
    - Região: us-east-1
    - Política de acesso: Público

### Amazon VPC (Virtual Private Cloud)

- **Rede**:
  - VPC:
    - CIDR Block: 10.0.0.0/16
  - Subnets:
    - Pública:
      - CIDR Block: 10.0.1.0/24
      - Acesso à internet via Internet Gateway
    - Privada:
      - CIDR Block: 10.0.2.0/24
      - Acesso à internet através de NAT Gateway

### Amazon Route 53

- **DNS**:
  - Domínio: myapp.com
  - Região: Global
  - Zonas hospedadas:
    - myapp.com
    - 
</div>

###

## Segurança

- **Grupos de Segurança**:
  - EC2:
    - HTTP (80), HTTPS (443) abertos para o público
  - RDS:
    - Acesso restrito à VPC

## Monitoramento

- **Amazon CloudWatch**:
  - Logs de aplicação e sistema
  - Métricas de desempenho

## Escalabilidade

- **Auto Scaling**:
  - Configurado para aumentar instâncias EC2 em horários de pico

## Considerações Finais

Esta infraestrutura foi projetada para suportar uma aplicação web básica, garantindo escalabilidade, segurança e disponibilidade utilizando os serviços gerenciados da AWS.

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" height="40" alt="go logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-plain.svg" height="40" alt="rust logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ruby/ruby-plain-wordmark.svg" height="40" alt="ruby logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dot-net/dot-net-plain-wordmark.svg" height="40" alt="dot-net logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain-wordmark.svg" height="40" alt="firebase logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" height="40" alt="amazonwebservices logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/circleci/circleci-plain.svg" height="40" alt="circleci logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" height="40" alt="kubernetes logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-plain-wordmark.svg" height="40" alt="docker logo"  />
</div>

###
