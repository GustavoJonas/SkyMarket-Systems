# SkyMarket-Systems
Projeto acadêmico com foco em práticas modernas de Cloud DevOps , abordando conteinerização, orquestração com Kubernetes, CI/CD, observabilidade e infraestrutura como código.

Contexto
A Loja Veloz é um e-commerce de médio porte que cresceu rapidamente e passou a enfrentar problemas recorrentes na produção, como indisponibilidades durante implantações, dificuldade de escalar em picos de acesso e baixa rastreabilidade de falhas entre serviços.

Este projeto propõe uma modernização da aplicação, adotando uma arquitetura baseada em microsserviços e práticas nativas em nuvem.

Objetivos
Padronizar o ambiente de desenvolvimento local
Reduzir riscos em implantações
Permitir escalabilidade automática
Aumentar observabilidade e confiabilidade
Automatizar o processo de entrega contínua
🏗️ Arquitetura da Aplicação
A aplicação é composta pelos seguintes serviços:

API Gateway – ponto de entrada HTTP
Serviço de Pedidos – criação e consulta de pedidos
Serviço de Pagamentos – integração com sistemas externos
Serviço de Estoque – reserva e baixa de itens
Banco de Dados – PostgreSQL
Mensageria (opcional) – comunicação assíncrona por eventos
A comunicação entre os serviços ocorre via HTTP REST, com possibilidade de eventos assíncronos para operações críticas.

Órfão Utilizado
Docker e Docker Compose
Kubernetes
GitHub Actions (CI/CD)
PostgreSQL
Prometeu / Grafana
Telemetria aberta
Terraformar
