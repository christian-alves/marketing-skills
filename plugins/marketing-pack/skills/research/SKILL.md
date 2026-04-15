---
description: Pesquisa de mercado com dados e fontes verificáveis. Gera relatórios com citações, estatísticas e tendências sobre qualquer tema de marketing. Use quando o usuário precisar de pesquisa fundamentada com referências reais.
---

# Pesquisa com Fontes Reais

Realiza pesquisa de mercado fundamentada e gera um relatório com fontes verificáveis.

**Você faz tudo. O usuário só fornece o tema.**

## O que coletar

Pergunte ao usuário (numa única mensagem):

1. **Tema da pesquisa** (obrigatório) — ex: "tendências de marketing digital 2026", "mercado de SaaS no Brasil"
2. **Objetivo** — informar estratégia, criar conteúdo, apresentar para cliente, pitch deck
3. **Público do relatório** — quem vai ler (CEO, equipe de marketing, investidores)
4. **Foco geográfico** — Brasil, LATAM, global
5. **Profundidade** — resumo executivo (1-2 páginas) ou relatório completo (5-10 páginas)

Se o usuário fornecer apenas o tema, assuma: objetivo = informar estratégia, público = equipe de marketing, foco = Brasil, profundidade = relatório completo.

## Processo de pesquisa

1. **Busque na web** usando as ferramentas disponíveis (WebSearch, WebFetch)
2. **Priorize fontes confiáveis**: relatórios de consultorias (McKinsey, Gartner, Statista), publicações do setor, estudos acadêmicos, dados oficiais (IBGE, Banco Central)
3. **Verifique cada dado**: nunca invente estatísticas. Se não encontrar um dado específico, diga "dado não encontrado" em vez de fabricar
4. **Cite tudo**: cada afirmação com dado deve ter [Fonte: nome, ano]

## Estrutura do relatório

Gere um arquivo Markdown (`research-report.md`):

### 1. Resumo Executivo
- 3-5 bullet points com as descobertas principais
- 1 parágrafo de conclusão

### 2. Contexto do Mercado
- Tamanho do mercado (valor, crescimento)
- Principais players
- Tendências macro que afetam o setor

### 3. Dados e Tendências
Para cada tendência encontrada:
- **O que é** (1-2 frases)
- **Evidência** (dado + fonte)
- **Implicação para marketing** (o que fazer com essa informação)

Mínimo 5 tendências, máximo 12.

### 4. Análise Competitiva
- 3-5 competidores ou referências relevantes
- O que cada um faz bem
- Oportunidades não exploradas

### 5. Recomendações
- 3-5 ações concretas baseadas nos dados
- Prioridade (alta/média/baixa)
- Esforço estimado (baixo/médio/alto)

### 6. Fontes
Lista completa de todas as fontes citadas:
```
1. [Nome da fonte] — "Título do relatório/artigo" (ano). URL
2. ...
```

## Regras de execução

1. **Nunca invente dados.** Se não encontrar, diga explicitamente
2. Sempre use WebSearch para buscar informações atualizadas
3. Cite a fonte de cada estatística no formato [Fonte: nome, ano]
4. Prefira dados de 2024-2026. Marque dados anteriores como "(dado de XXXX)"
5. Escreva em português (PT-BR)
6. Salve como `research-report.md` no diretório atual
7. Após gerar, pergunte: "Quer que eu aprofunde algum ponto?"

## Exemplo de citação

> O mercado de IA generativa deve atingir US$ 1,3 trilhão até 2032 [Fonte: Bloomberg Intelligence, 2023], com crescimento anual de 42%.
