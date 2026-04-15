---
description: Gera carrosséis completos para Instagram com copy, estrutura de slides e legenda. Cria o conteúdo editorial pronto para design. Use quando o usuário quiser criar um carrossel para redes sociais.
---

# Carrossel para Instagram

Gera um carrossel completo com copy dos slides e legenda, pronto para design.

**Você faz tudo. O usuário só fornece o tema.**

## O que coletar

Pergunte ao usuário (numa única mensagem):

1. **Tema do carrossel** (obrigatório)
2. **Marca/perfil** — nome e @ do Instagram
3. **Objetivo** — educar, vender, gerar leads, engajamento
4. **CTA desejado** — comentário com palavra-chave, link na bio, salvar post
5. **Tom** — casual, técnico, provocativo, inspiracional
6. **Número de slides** — padrão: 8-10

Se o usuário fornecer apenas o tema, assuma: tom provocativo/educativo, 8 slides, CTA de comentário.

## Estrutura dos slides

### Slide 1 — Capa (Hook)
- **Headline**: frase curta e impactante que gera curiosidade ou promete transformação
- Máximo 8 palavras
- Pode usar número ("5 formas de...", "O erro que...")
- Deve fazer a pessoa parar de scrollar

### Slide 2 — Contexto / Índice
- Apresenta o que a pessoa vai aprender
- Lista numerada ou frase que cria expectativa
- Ex: "São 5 passos simples. Arraste →"

### Slides 3 a N-1 — Conteúdo
Para cada slide de conteúdo:
- **Título**: ação ou conceito em 3-5 palavras (ALL CAPS)
- **Corpo**: 1-3 frases curtas explicando o ponto
- **Dica/exemplo**: se aplicável, um exemplo concreto
- 1 ideia por slide — nunca misture conceitos

### Slide N — CTA (último)
- Reforça o valor: "Quer [resultado]?"
- CTA claro: "Comenta '[PALAVRA]' que eu te mando [entregável]"
- Ou: "Salva pra consultar depois 🔖"
- Menciona o @ do perfil

## Formato de saída

Gere um arquivo Markdown (`carousel.md`) com:

```markdown
# [Título do Carrossel]

**Perfil:** @handle
**Slides:** N
**CTA:** [palavra-chave]

---

## Slide 01 — Capa
**[HEADLINE DO SLIDE]**

---

## Slide 02 — Índice
**[HEADLINE]**
[Corpo do slide]

---

## Slide 03 — [Título do Passo]
**[HEADLINE]**
[Corpo do slide]

---
[...]

## Slide NN — CTA
**[HEADLINE]**
[Texto do CTA]

---

## Legenda

[Legenda completa pronta para copiar e colar]

---

## Hashtags

#hashtag1 #hashtag2 ... (10 hashtags)
```

## Regras para a legenda

- **Hook** (1 frase): resultado, provocação ou novidade
- **Corpo** (2-3 frases): o que/como, curto e escaneável
- **CTA**: "Comenta '[PALAVRA]' que eu te mando [o que recebe]"
- **Opcional**: "Salva esse post pra quando precisar 🔖"
- **Hashtags**: 10, mix de amplas e nichadas
- Português (PT-BR), tom casual
- Máximo 2 emojis em toda a legenda

## Regras de conteúdo

1. Headlines: ALL CAPS, máximo 8 palavras por slide
2. Corpo: frases curtas, parágrafos de 1-2 linhas
3. 1 ideia por slide — nunca mais
4. Linguagem direta, sem enrolação
5. Exemplos concretos sempre que possível
6. Primeiro slide PRECISA gerar curiosidade (é o que aparece no feed)
7. Último slide PRECISA ter CTA forte

## Regras de execução

1. Gere todos os slides de uma vez
2. Escreva em português (PT-BR)
3. Salve como `carousel.md` no diretório atual
4. Após gerar, pergunte: "Ficou bom? Quer que eu ajuste algum slide ou mude o tom?"
