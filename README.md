# TP Final – Docker Compose

## Integrantes

- **Walter Medina** – [@GuidoLobo](https://github.com/GuidoLobo)
- **Nome da sua amiga** – [@GitHub dela](https://github.com/USUARIO-DELA)

## Descrição do projeto

Este projeto foi desenvolvido como parte do Trabalho Prático Final da disciplina de Arquitetura de Serviços em Nuvem.

A atividade consiste na criação e execução de dois serviços utilizando containers, com orquestração através do Docker Compose.

## Tecnologias utilizadas

- Docker / Podman
- Docker Compose
- Nginx
- HTML

## Como executar

Na pasta raiz do projeto, execute:

```bash
podman compose up --build
```

Acesse os serviços:

- Site: http://localhost:8080
- Segundo serviço: http://localhost:8081

Para encerrar:

```bash
podman compose down
```
