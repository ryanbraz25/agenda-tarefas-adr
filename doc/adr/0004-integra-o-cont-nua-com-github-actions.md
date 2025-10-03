# 4. Integração contínua com GitHub Actions

## Status
Aceito

## Contexto
Quero que o projeto rode checagens automáticas a cada push no GitHub, sem precisar configurar nada além do repositório.

## Decisão
Usar **GitHub Actions** para executar validações simples (por exemplo, testes ou linters) em cada commit e pull request.

## Consequências
Ajuda a detectar erros cedo e padroniza as verificações do projeto.
Depende de arquivos de workflow no repositório e da infraestrutura do GitHub.

