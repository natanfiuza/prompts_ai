# Formato dos prompts

Cada prompt é um arquivo Markdown com frontmatter YAML (`title`, `slug`, `category`, `tags`, `summary`) e um corpo autossuficiente. Escolhemos esse formato para que a futura ferramenta do devtools possa indexar e buscar os prompts a partir dos metadados, sem impedir que alguém copie o texto manualmente.

## Opções consideradas

- **Sem metadados:** simples, mas a ferramenta teria de inferir título, categoria e resumo pelo caminho e pelo conteúdo.
- **Manifesto separado (`catalog.json`):** centraliza a indexação, mas duplica informação e exige manter dois arquivos sincronizados a cada novo prompt.
