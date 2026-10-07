# Be One — instruções para Claude

O segundo cérebro da agência fica em `cerebro/` (cofre do Obsidian).

- Comece por `cerebro/system-map.md` e siga os links `[[...]]` só até o que a tarefa precisa.
- Para escolher ferramenta (skill, plugin ou conector), consulte `cerebro/ferramentas/Mapa de ferramentas.md`.
- Cliente: ficha em `cerebro/clientes/<nome>.md`; dados operacionais atualizados ficam no Notion (link na ficha).
- Ao aprender algo durável sobre um cliente, anote na seção `## Notas` da ficha.
- Ao tomar uma decisão relevante, adicione uma linha em `cerebro/decisoes/Registro de decisões.md`.
- Use `[[wikilinks]]` ao criar notas novas, para que apareçam no gráfico.

## Fila do Escritório (tarefas reais)

O escritório (https://claude.ai/artifact/XnoksXQfH3VFFpr9EoGw4m) mostra só tarefas reais. Toda equipe registra o próprio trabalho lá com a ferramenta `ArtifactData` (url acima, coleção `tarefas`):

1. Ao receber um pedido: procure a tarefa na fila (`action: "list"`). Se não existir, crie com `set` e um `doc_id` curto, com `{titulo, cliente, equipe, motivo, status: "fila", criado: <epoch ms>}`.
2. Ao começar: `update` com `{status: "fazendo", agente: "<equipe>"}` e o `if_version` lido.
3. Ao terminar: `update` com `{status: "feito", resultado: "<o que foi entregue, com link se houver>"}`.
4. Nunca crie tarefa de exemplo nem marque como feito o que não foi entregue.

Se `ArtifactData` não estiver disponível na sessão, diga isso ao Lucas e registre a tarefa no Notion.

## Memória compartilhada com o Claude do chat

O Claude do claude.ai não lê este repositório. O que ele precisa saber fica na página do Notion **"Contexto do Claude — Be One"** (https://app.notion.com/p/3f29fe6df06d81e8969fd3c81368e594). Sempre que houver decisão, modelo aprovado, cliente novo ou regra de trabalho, acrescente lá também (decisão nova no topo da tabela).
