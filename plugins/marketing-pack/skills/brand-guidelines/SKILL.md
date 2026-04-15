---
description: Gera um guia completo de brand guidelines a partir de informações da marca. Extrai paleta de cores, tipografia, tom de voz e regras de uso. Use quando o usuário quiser criar ou documentar a identidade visual de uma marca.
---

# Brand Guidelines Generator

Cria um documento completo de brand guidelines a partir das informações fornecidas pelo usuário.

**Você faz tudo. O usuário só fornece as informações da marca.**

## O que coletar

Pergunte ao usuário (numa única mensagem, cobrindo tudo que faltar):

1. **Nome da marca** (obrigatório)
2. **Setor/nicho** (obrigatório)
3. **Cores da marca** — se tiver, pedir os hexadecimais; se não, sugerir paleta baseada no setor
4. **Fontes** — se tiver; se não, sugerir combinação adequada
5. **Tom de voz** — formal, casual, técnico, inspiracional, etc.
6. **Público-alvo** — quem a marca quer atingir
7. **Logo** — descrição ou arquivo, se disponível
8. **Referências** — marcas que admira ou quer se parecer

Se o usuário fornecer um site ou rede social da marca, analise para extrair cores, fontes e tom automaticamente antes de perguntar.

## Estrutura do documento

Gere um arquivo Markdown (`brand-guidelines.md`) com as seguintes seções:

### 1. Visão da Marca
- Missão (1 frase)
- Visão (1 frase)
- Valores (3-5 palavras-chave)
- Proposta de valor única

### 2. Paleta de Cores
Para cada cor, incluir:
- Nome da cor (ex: "Azul Primário")
- Hexadecimal, RGB e HSL
- Quando usar (ex: "títulos e CTAs")
- Quando NÃO usar

Incluir: cor primária, secundária, acento, neutros (claro e escuro), cor de sucesso, erro e alerta.

Formato:
```
| Cor | Hex | RGB | Uso |
|-----|-----|-----|-----|
| Primária | #0032BF | 0, 50, 191 | Headlines, botões, links |
```

### 3. Tipografia
- Fonte de títulos (nome + peso + fallback)
- Fonte de corpo (nome + peso + fallback)
- Hierarquia: H1, H2, H3, body, caption (tamanho + peso + line-height)
- Espaçamento entre letras recomendado

### 4. Tom de Voz
- 3 adjetivos que definem o tom
- Exemplos de "faça assim" vs "não faça assim" (mínimo 3 pares)
- Palavras a usar com frequência (5-10)
- Palavras a evitar (5-10)
- Exemplo de post para Instagram (1 parágrafo)
- Exemplo de e-mail (1 parágrafo)

### 5. Uso do Logo
- Tamanho mínimo
- Área de proteção (safe zone)
- Variações permitidas (fundo claro, fundo escuro, monocromático)
- Usos proibidos (distorção, rotação, cores erradas)

### 6. Elementos Visuais
- Estilo de fotografia/imagem
- Estilo de ícones
- Cantos (arredondados ou retos)
- Sombras (sim/não, intensidade)
- Espaçamento e grid

### 7. Aplicações
- Exemplo de post Instagram (descrição visual)
- Exemplo de capa de apresentação
- Exemplo de assinatura de e-mail
- Exemplo de cartão de visita (layout descrito)

## Regras de execução

1. Sempre gere o arquivo completo — nunca parcial
2. Use Markdown com tabelas e formatação rica
3. Se o usuário não souber algo (ex: cores), sugira com justificativa baseada no setor e público
4. Pergunte tudo de uma vez — não faça várias rodadas de perguntas
5. Salve como `brand-guidelines.md` no diretório atual
6. Após gerar, pergunte: "Quer que eu ajuste algo?"
