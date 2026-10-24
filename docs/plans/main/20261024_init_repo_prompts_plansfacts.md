# Plano — Inicialização do repositório de prompts

- **Data:** 2026-10-24
- **Branch:** main
- **Task:** init_repo_prompts
- **Status:** aprovado

## Contexto

O repositório `prompts_ia` vai conter uma coletânea de prompts úteis em português, base para uma futura ferramenta do devtools.natanfiuza.dev.br. Até então continha apenas `anti_virus/limpeza_virus.md`, um vídeo de referência e um atalho `.lnk` local.

## Decisões

1. Repositório público, licença MIT, README em pt-BR.
2. Prompts em Markdown com frontmatter YAML (`title`, `slug`, `category`, `tags`, `summary`) e corpo autossuficiente.
3. Pastas-tema na raiz; README por pasta e README raiz com tabela de categorias.
4. Frontmatter aplicado ao prompt existente, com `slug: limpeza_virus` e `category: anti_virus`.
5. O `.lnk` fica fora do git (`*.lnk`); o link `https://linktr.ee/Sintesetech` é preservado no README da pasta.
6. `Thumbs.db` e `desktop.ini` também entram no `.gitignore`; o vídeo é versionado.
7. `docs/plans/`, `docs/survey/` e `docs/adr/` são versionados.
8. O ADR `docs/adr/0001-formato-dos-prompts.md` registra o formato escolhido.
9. `git init` local na branch `main`, sem remoto; o remoto será criado manualmente.
10. `CLAUDE.md` atualizado com as convenções.

## Execução

1. `git init -b main`.
2. Criar `.gitignore`, `LICENSE`, `README.md`, `anti_virus/README.md` e `docs/adr/0001-formato-dos-prompts.md`.
3. Adicionar frontmatter a `anti_virus/limpeza_virus.md`.
4. Atualizar `CLAUDE.md`.
5. Criar `docs/plans/main/20261024_init_repo_prompts_plansfacts.md` e `docs/survey/20261024_init_repo_prompts_surveyfacts.md`.
6. Executar `git add -A` e o commit inicial com a linha `Co-Authored-By: Claude Code <noreply@anthropic.com>`.

## Validação

- `git status` limpo após o commit.
- Frontmatter YAML válido no prompt.
- Links relativos do README funcionando.
- `.lnk` ausente do índice do git e vídeo presente.
