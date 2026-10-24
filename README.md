# Prompts IA

Coletânea de prompts úteis em português para usar com assistentes de IA — base de conteúdo para a futura ferramenta do [devtools.natanfiuza.dev.br](https://devtools.natanfiuza.dev.br).

## O que é

Cada prompt é um arquivo Markdown autossuficiente: o texto pode ser copiado inteiro e colado em um assistente de IA. O frontmatter YAML no topo permite que uma ferramenta leia, indexe e busque os prompts automaticamente.

## Categorias

| Categoria | Descrição | Prompts |
| --- | --- | --- |
| [Anti-vírus](anti_virus/README.md) | Diagnóstico e remoção de vírus no Windows | 1 |

## Como usar um prompt

1. Abra a pasta da categoria e leia o `README.md` dela para entender o que o prompt faz e como usá-lo.
2. Abra o arquivo `.md` do prompt e copie o conteúdo a partir do primeiro parágrafo depois do frontmatter.
3. Cole no assistente de IA e siga as instruções que ele der.

## Como adicionar um prompt

1. Crie uma pasta com o nome da categoria (minúsculas, sem acento, com `_` no lugar de espaços), se ela ainda não existir.
2. Adicione um arquivo `.md` com nome em minúsculas e `_` no lugar de espaços.
3. Inclua o frontmatter:

```yaml
---
title: Título do prompt
slug: nome_do_arquivo_sem_extensao
category: nome_da_pasta
tags: [tag-1, tag-2]
summary: Uma frase sobre o que o prompt faz.
---
```

4. Escreva o corpo do prompt de forma autossuficiente, em português.
5. Crie ou atualize o `README.md` da pasta seguindo o padrão das categorias existentes.

## Estrutura

```text
.
├── anti_virus/
│   ├── README.md
│   ├── limpeza_virus.md
│   └── quem_usa_seu_pc.mp4
├── docs/
│   └── adr/
├── CLAUDE.md
├── LICENSE
└── README.md
```

## Licença

[MIT](LICENSE) © 2026 Nataniel Fiuza
