---
name: estrategia-google-ads
description: Método da Be One para montar a estratégia de Google Ads de um cliente, no modelo usado na Scomptec. Use quando o Lucas pedir estratégia, planejamento, estrutura ou montagem de campanha de Google Ads, ou disser que chegaram os dados de produto de um cliente de Google Ads (ex.: Typmann).
---

# Estratégia de Google Ads (método Scomptec)

Referência real: cliente Scomptec no Notion — briefing de produtos (Projetos) e "Diário de Otimização | Google Ads Scomptec". Leia esses dois antes de começar; eles são o padrão de qualidade.

## Entradas obrigatórias

Do cliente (ficha no Notion e `cerebro/clientes/`):
- Produtos/linhas em ordem de prioridade comercial
- Como o comprador pesquisa: nomes técnicos, códigos, sinônimos, marcas, o problema que ele vê (na Scomptec: o alarme da máquina)
- Quem decide a compra e quem pesquisa (pode ser diferente)
- Segmentos e clientes de referência, regiões atendidas
- Ticket, margem, pedido mínimo, capacidade
- Diferenciais reais e o que o site promete
- Como o lead chega hoje e quem responde

Se faltar algo, pergunte ao Lucas e registre a pergunta na Fila do Escritório (campo `pergunta`). Não invente produto, marca, promessa ou número.

## Entregável: documento de estratégia (Claude Docs)

1. **Resumo do negócio** em 3 linhas e o objetivo da campanha (ex.: Scomptec 85% cliente final, 15% parceiros).
2. **Mapa de intenção → grupos de anúncios** (tabela: grupo, intenção, palavras-exemplo, página de destino). Separar sempre:
   - termos com marca/fabricante, termos sem marca (onde costuma estar o volume), modelos e códigos, o problema/sintoma, portas de entrada (produto simples que abre a conversa), concorrentes ou plataformas parceiras quando fizer sentido (Scomptec: Mazak usa drive Mitsubishi).
3. **Palavras-chave** por grupo (frase e exata), com volume e lance de topo de página do Planejador quando disponível.
4. **Negativas**: lista compartilhada geral (emprego, grátis, curso, setores errados) + negativas cruzadas entre grupos para cada busca cair no anúncio mais específico.
5. **Locais**: Brasil ou raios por cidade/polo, segmentação por presença.
6. **Campanha**: só Rede de Pesquisa, IA Max desligada, maximizar cliques com teto de CPC (definido pelo Planejador), verba diária proposta. Sem PMax (o Lucas não gosta).
7. **Anúncios**: RSA por grupo usando só promessas que estão no site ou aprovadas; 6 sitelinks e 4 frases de destaque; recurso de WhatsApp/ligação.
8. **Medição antes de gastar**: conversões (WhatsApp, formulário, telefone), Tag Manager, GA4 vinculado, Clarity. Listar o que o site precisa (botão de WhatsApp, formulário curto, links tel:).
9. **Regras da conta**: não mexer em lance ou estrutura antes de 100 cliques; trocar para maximizar conversões com 15–20 conversões; publicação é sempre clique do Lucas.
10. **Pendências** com o cliente e com o site, em checklist.

## Depois de aprovada

- Criar no Notion, dentro da página do cliente, o "Diário de Otimização | Google Ads <Cliente>" no mesmo formato da Scomptec: estado atual da conta, grupos, diário de mudanças (linha nova no topo), pendências, regras.
- Registrar a decisão em `cerebro/decisoes/Registro de decisões.md` e atualizar a ficha do cliente.
