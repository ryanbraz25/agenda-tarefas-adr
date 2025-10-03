# Agenda de Tarefas — ADR

Este repositório tem um projeto simples de agenda de tarefas e os registros das decisões de arquitetura (ADRs).

## O que são ADRs
ADRs são arquivos de texto onde registramos decisões importantes do projeto (o que foi decidido e por quê).  
Isso ajuda a lembrar e explicar escolhas no futuro.

## Como registrei
Usei a ferramenta **adr-tools** no Linux:
- `adr init doc/adr` para criar a pasta de registros.
- `adr new "TÍTULO"` para cada decisão.

Os arquivos ficam em `doc/adr`.

## Decisões deste projeto
1. **Arquitetura em camadas** (frontend, backend e banco de dados).  
2. **Banco de dados relacional (PostgreSQL)** para começar simples.  
3. **Integração contínua com GitHub Actions** para checar o projeto a cada push.

Essas decisões deixam o projeto mais organizado e fácil de manter.

