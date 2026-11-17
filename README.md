# Skills públicas

Skills em português para estruturar brainstorms, pesquisas e prospecção B2B.

| Skill | Para que serve | Variantes |
| --- | --- | --- |
| [Brainstorm](skills/codex/skill-brainstorm/SKILL.md) | Define o briefing, explora o problema por ângulos diferentes e sintetiza as opções. | Codex, Agents e Claude |
| [Pesquisa Alex](skills/codex/pesquisa-alex/SKILL.md) | Estrutura pesquisas com perguntas decisivas, fontes rastreáveis e etapas de revisão. | Codex, Agents e Claude |
| [Prospecção B2B](skills/codex/prospeccao-b2b/SKILL.md) | Planeja a descoberta e a qualificação de empresas e decisores e prepara a lista para a próxima etapa. | Codex |

## Instalação

Clone ou baixe este repositório. Copie a **pasta inteira** de cada skill, com
suas referências e scripts, para o diretório de skills do seu ambiente:

| Origem neste repositório | Destino local |
| --- | --- |
| [`skills/codex/`](skills/codex/) | `~/.codex/skills/` |
| [`skills/agents/`](skills/agents/) | `~/.agents/skills/` |
| [`skills/claude/`](skills/claude/) | `~/.claude/skills/` |

Para usar o fluxo completo da Pesquisa Alex, instale as seis pastas
`pesquisa-alex*` da mesma variante. Além da skill principal, elas incluem
`pesquisa-alex-discover`, `pesquisa-alex-add-items`,
`pesquisa-alex-add-fields`, `pesquisa-alex-deep` e `pesquisa-alex-report`.

Os validadores de resultados da Pesquisa Alex usam Python 3 e PyYAML.
Instale o PyYAML no ambiente Python que vai executar esses scripts
(`python3 -m pip install PyYAML`).
