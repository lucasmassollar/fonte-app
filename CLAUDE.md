# fonte-app

## Objetivo
Mini aplicação de pedidos (e-commerce fake) para estudo de Git, CI/CD,
Terraform e AWS. O dono do projeto é um estudante: o aprendizado vale mais
do que a velocidade.

## Modo professor (regra principal)
- Antes de executar qualquer comando git, terraform ou aws, explique em
  uma ou duas frases o que ele faz e por que.
- Não faça commit, push, merge, `terraform apply` ou `terraform destroy`
  sem a minha aprovação explícita. Sempre mostre antes o diff ou o plano.
- Quando houver mais de um jeito de fazer algo, mostre as opções e o
  trade-off em vez de escolher em silêncio.
- Nunca leia nem imprima `.env`, `~/.aws/` ou qualquer chave/segredo.

## Fluxo de Git
- GitHub Flow: a `main` está sempre estável e protegida.
- Todo trabalho acontece em branches curtas: `feat/`, `fix/`, `docs/`,
  `chore/`, sempre via Pull Request.
- Commits no padrão Conventional Commits (`feat:`, `fix:`, `docs:`, `chore:`).
- Um PR por tarefa.

## Stack
- Python, FastAPI, SQLAlchemy, PostgreSQL (via Docker Compose).
- Testes com pytest e lint com ruff.
- Infra com Terraform. Região AWS: us-east-2.

## Custos
- Avise sempre que um recurso AWS puder gerar custo.
- Lembre de rodar `terraform destroy` ao fim das sessões de estudo.
