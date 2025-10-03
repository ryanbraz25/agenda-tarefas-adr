# 2. Arquitetura em camadas (frontend, backend e banco de dados)

## Status
Aceito

## Contexto
O sistema será uma agenda de tarefas simples, acessada pelo navegador.
Quero organizar o código de forma clara para facilitar manutenção no futuro.

## Decisão
Escolhi usar a arquitetura em camadas:  
- **Frontend**: parte visual (interface do usuário).  
- **Backend**: regras de negócio e API.  
- **Banco de dados**: armazenamento das informações.

## Consequências
Essa escolha facilita manutenção, permite trocar tecnologias no futuro com menos impacto
e deixa o projeto mais organizado desde o início.

