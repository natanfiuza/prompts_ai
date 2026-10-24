# Levantamento — Inicialização do repositório de prompts

- **Data:** 2026-10-24
- **Task:** init_repo_prompts
- **Branch:** main

## Contexto

Repositório destinado a uma coletânea de prompts úteis em português, que servirá de base para uma nova ferramenta em devtools.natanfiuza.dev.br. Estado inicial: `anti_virus/limpeza_virus.md`, `anti_virus/quem_usa_seu_pc.mp4`, um atalho `.lnk` e `CLAUDE.md`.

## Fatos levantados

- Git 2.55.0.windows.5 instalado; `gh` não instalado.
- Identidade git configurada: Nataniel Fiuza <natan.fiuza@gmail.com>.
- `devtools.natanfiuza.dev.br` responde com o título "Tools - devtools." e não detalha ferramentas.
- O `.lnk` aponta para `https://linktr.ee/Sintesetech` (aberto via Chrome local).
- O vídeo tem 5,7 MB; o prompt tem 4,8 KB.
- Não havia repositório git, README ou LICENSE.

## Decisões por rodada

### Rodada 1

- Q1: repositório público, licença MIT.
- Q2: frontmatter YAML + corpo autossuficiente.
- Q3: qualquer assunto, organizado por pastas-tema.
- Q4: git local na `main`, sem remoto (criado manualmente).
- Q5: README em pt-BR com as seções acordadas.
- Q6: não respondida na rodada 1.

### Rodada 2

- Q6 (reformulada): o link do atalho deve ir para um README dentro de `anti_virus/`.
- Q7: pastas-tema na raiz.
- Q8: convenções do frontmatter e migração do prompt aprovadas.
- Q9: LICENSE MIT, Copyright (c) 2026 Nataniel Fiuza.
- Q10: título "Prompts IA", tagline e índice de categorias.
- Q11: versionar `docs/plans/` e `docs/survey/` (não ignorar).
- Q12: criar ADR; sem glossário.

### Rodada 3

- Q13: README por pasta + README raiz com tabela de categorias.
- Q14: `.lnk` fora do git; link preservado no README.
- Q15: conteúdo do `anti_virus/README.md` aprovado.

## Entendimento final

Aprovado pelo usuário em 2026-10-24.
