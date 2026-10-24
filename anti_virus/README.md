# Limpeza de vírus no Windows

Prompt que vasculha o Windows atrás de mineradores de criptomoeda, trojans e outros vírus, explica o que encontrou e, com autorização, remove tudo pela raiz.

## O que o prompt faz

- Verifica o computador em modo somente leitura: processos, inicialização automática, serviços, tarefas agendadas, conexões de rede, Windows Defender, arquivo hosts e assinaturas WMI.
- Apresenta um diagnóstico em tabela, com nível de suspeita e uma explicação para quem não é técnico.
- Pede autorização explícita antes de remover qualquer coisa.
- Remove processos, tarefas, serviços, chaves de registro, arquivos e exclusões do antivírus, e bloqueia os endereços usados pela ameaça.
- Confirma a limpeza com uma nova verificação e com o Microsoft Defender.
- Orienta sobre troca de senhas, verificação em duas etapas e quando vale formatar o computador.

## Fonte

- [Linktree Sintesetech](https://linktr.ee/Sintesetech)
- Vídeo de referência: [quem_usa_seu_pc.mp4](quem_usa_seu_pc.mp4)

## Como usar

1. Abra um assistente de IA com acesso ao terminal do Windows (por exemplo, o Claude Code) como administrador.
2. Copie o conteúdo de [limpeza_virus.md](limpeza_virus.md) a partir do primeiro parágrafo depois do frontmatter.
3. Cole no assistente e responda à pergunta inicial sobre os sintomas do computador.
4. Revise a lista de itens que o assistente propõe remover antes de autorizar qualquer remoção.

> **Aviso:** o prompt executa comandos que removem programas, arquivos e configurações. Revise a lista apresentada e faça backup dos seus dados antes de autorizar.

## Arquivos

- [limpeza_virus.md](limpeza_virus.md) — o prompt.
- [quem_usa_seu_pc.mp4](quem_usa_seu_pc.mp4) — vídeo de referência.
