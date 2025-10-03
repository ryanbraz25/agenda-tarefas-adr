# 3. Banco de dados relacional (PostgreSQL)

## Status
Aceito

## Contexto
O sistema vai armazenar usuários e tarefas com relações simples (ex: um usuário tem várias tarefas).  
Preciso de um banco de dados fácil de aprender e configurar, já que o projeto é pequeno e acadêmico.

## Decisão
Escolhi usar um banco de dados relacional, especificamente o **PostgreSQL**.  
Ele é gratuito, popular e funciona bem para esse tipo de sistema.

## Consequências
Teremos tabelas organizadas com integridade referencial.  
O SQL é fácil de encontrar exemplos e tutoriais.  
Em mudanças futuras de estrutura, pode ser necessário fazer migrações de esquema.

