---
description: Cria briefings profissionais de campanha de marketing com público-alvo, canais, cronograma e KPIs. Use quando o usuário precisar planejar uma campanha, lançamento ou ação de marketing.
---

# Briefing de Campanha

Cria um briefing completo e profissional de campanha de marketing.

**Você faz tudo. O usuário só fornece o produto/serviço e o objetivo.**

## O que coletar

Pergunte ao usuário (numa única mensagem, cobrindo tudo que faltar):

1. **Produto/serviço** (obrigatório) — o que está sendo promovido
2. **Objetivo da campanha** — lançamento, vendas, awareness, captação de leads, reativação
3. **Público-alvo** — se souber; se não, você define com base no produto
4. **Orçamento** — se tiver; se não, gere versões para 3 faixas (baixo/médio/alto)
5. **Prazo** — quando começa e quando termina
6. **Canais preferidos** — Instagram, e-mail, Google Ads, TikTok, etc. Se não souber, você recomenda
7. **Tom da campanha** — urgente, educativo, aspiracional, promocional
8. **Referências** — campanhas que admira

Se o usuário fornecer apenas o produto, assuma defaults razoáveis e gere o briefing completo.

## Estrutura do briefing

Gere um arquivo Markdown (`campaign-brief.md`):

### 1. Resumo da Campanha
- Nome sugerido da campanha (criativo, memorável)
- Objetivo em 1 frase
- Período: [data início] a [data fim]
- Investimento estimado

### 2. Público-Alvo
- **Perfil demográfico**: idade, gênero, localização, renda
- **Perfil comportamental**: interesses, hábitos digitais, dores, desejos
- **Persona principal**: nome fictício + descrição de 3-4 linhas
- **Persona secundária** (se aplicável)

### 3. Proposta de Valor
- Mensagem central da campanha (1 frase)
- 3 argumentos de suporte
- Diferencial competitivo (por que escolher isso e não o concorrente)

### 4. Estratégia de Canais

Para cada canal recomendado:

| Canal | Objetivo | Formato | Frequência | Investimento |
|-------|----------|---------|------------|-------------|
| Instagram | Awareness | Reels + Carrosséis | 5x/semana | 40% |
| E-mail | Conversão | Sequência 5 e-mails | Dias 1,3,5,7,10 | 10% |

### 5. Cronograma

Fase por fase:

| Fase | Período | Ações | Responsável |
|------|---------|-------|-------------|
| Pré-lançamento | Sem 1-2 | Teasers, lista de espera | Marketing |
| Lançamento | Sem 3 | Campanha principal, ads | Marketing + Vendas |
| Sustentação | Sem 4-6 | Retargeting, prova social | Marketing |

### 6. Conteúdo Necessário

Lista de peças a produzir:
```
□ 5 Reels (roteiros)
□ 3 Carrosséis (temas)
□ 1 Landing page (copy)
□ 5 E-mails (sequência)
□ 3 Criativos para ads (formatos)
□ 1 Página de vendas (se aplicável)
```

### 7. KPIs e Metas

| Métrica | Meta | Como medir |
|---------|------|------------|
| Alcance | 50K | Instagram Insights |
| Leads captados | 500 | Formulário/ManyChat |
| Taxa de conversão | 3% | Checkout/Analytics |
| CAC | R$ XX | Investimento ÷ clientes |
| ROAS | 3x | Receita ÷ investimento em ads |

### 8. Riscos e Contingências
- 3 riscos possíveis com plano B para cada

## Regras de execução

1. Gere o briefing completo — nunca parcial
2. Se o usuário não informar orçamento, crie 3 cenários (R$ 500, R$ 2.000, R$ 5.000)
3. Adapte os canais ao perfil do público, não ao que está na moda
4. Datas devem ser absolutas (não "semana 1", mas "05/05 a 11/05")
5. Escreva em português (PT-BR)
6. Salve como `campaign-brief.md` no diretório atual
7. Após gerar, pergunte: "Quer que eu detalhe alguma fase ou crie o conteúdo de alguma peça?"
