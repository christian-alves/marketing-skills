---
description: Cria sequências completas de e-mail marketing com assuntos otimizados, corpo persuasivo e CTAs estratégicos. Use quando o usuário precisar de uma sequência de e-mails para lançamento, nutrição de leads, onboarding ou vendas.
---

# Sequência de E-mail Marketing

Cria fluxos completos de e-mail com copy profissional, assuntos otimizados e CTAs estratégicos.

**Você faz tudo. O usuário só fornece o produto e o objetivo.**

## O que coletar

Pergunte ao usuário (numa única mensagem):

1. **Produto/serviço** (obrigatório) — o que está vendendo ou promovendo
2. **Tipo de sequência** — lançamento, nutrição de leads, onboarding, carrinho abandonado, reativação, pós-compra
3. **Número de e-mails** — padrão: 5
4. **Intervalo entre e-mails** — padrão: dias 1, 3, 5, 7, 10
5. **Tom** — persuasivo, educativo, casual, urgente
6. **Público** — quem vai receber (leads frios, lista quente, clientes)
7. **Oferta/CTA principal** — comprar, agendar call, baixar material, se inscrever
8. **Preço** (se aplicável)
9. **Nome do remetente** — como assina os e-mails

Se o usuário fornecer apenas o produto, assuma: sequência de lançamento, 5 e-mails, tom persuasivo, intervalo padrão.

## Estrutura de cada e-mail

Para cada e-mail, gere:

### Cabeçalho
- **Assunto principal** — otimizado para abertura (máximo 50 caracteres)
- **Assunto alternativo** — para teste A/B
- **Preview text** — texto que aparece após o assunto na inbox (40-90 caracteres)
- **Dia de envio** — ex: Dia 1, Dia 3

### Corpo
O e-mail em si, com:
- **Abertura** (1-2 frases): hook que conecta com a dor/desejo do leitor
- **Corpo** (2-4 parágrafos curtos): história, argumento ou prova social
- **CTA** (1 frase + botão): ação clara e específica
- **P.S.** (opcional): urgência, bônus ou lembrete

### Notas técnicas
- Segmento: quem recebe este e-mail
- Condição: o que precisa acontecer para enviar (ex: "não abriu e-mail 2")
- Objetivo: awareness, consideração ou conversão

## Tipos de sequência

### Lançamento (5-7 e-mails)
1. **Antecipação** — "Algo novo está chegando"
2. **Educação** — problema que o produto resolve
3. **Prova social** — resultados, depoimentos, caso de uso
4. **Oferta** — apresentação do produto + preço + bônus
5. **Urgência** — "Últimas horas" / escassez
6. (Opcional) **Última chance** — "Encerramento hoje"
7. (Opcional) **Pós-fechamento** — "Perdeu? Veja o que aconteceu"

### Nutrição de Leads (5 e-mails)
1. **Boas-vindas** — entrega o lead magnet + apresentação
2. **Valor** — dica/insight relacionado ao problema
3. **Autoridade** — sua história ou caso de sucesso
4. **Objeções** — responde as dúvidas mais comuns
5. **Transição** — convite suave para o próximo passo

### Carrinho Abandonado (3 e-mails)
1. **Lembrete** (1h depois) — "Você esqueceu algo"
2. **Objeção** (24h depois) — responde a principal dúvida
3. **Urgência** (48h depois) — desconto ou bônus por tempo limitado

## Formato de saída

Gere um arquivo Markdown (`email-sequence.md`):

```markdown
# Sequência: [Nome da Sequência]

**Produto:** [nome]
**Tipo:** [lançamento/nutrição/etc]
**E-mails:** [quantidade]
**Intervalo:** [dias]
**Tom:** [persuasivo/educativo/etc]

---

## E-mail 01 — [Título interno]
**Dia:** 1
**Assunto:** [assunto principal]
**Assunto B:** [alternativo para teste A/B]
**Preview:** [preview text]
**Segmento:** [quem recebe]

---

[Corpo completo do e-mail aqui]

**[TEXTO DO BOTÃO CTA]**

P.S.: [texto do P.S.]

---
**Notas:** [condições, objetivo]

---

## E-mail 02 — [Título interno]
[...]
```

## Regras de copy

1. **Assuntos**: curtos (< 50 chars), geram curiosidade, evitam palavras spam (grátis, urgente, oferta)
2. **Abertura**: nunca comece com "Olá [nome]". Comece com uma frase que prenda
3. **Parágrafos**: máximo 3 linhas. Muitos parágrafos de 1 linha
4. **CTA**: 1 CTA principal por e-mail. Repita no máximo 2x (meio e fim)
5. **Tom**: como se estivesse escrevendo para um amigo inteligente
6. **P.S.**: use em pelo menos 3 dos e-mails — é a segunda parte mais lida
7. **Escassez**: use apenas se for real (prazo, vagas limitadas, bônus temporário)

## Regras de execução

1. Gere a sequência completa — todos os e-mails de uma vez
2. Escreva em português (PT-BR)
3. Inclua assunto A e B para todos os e-mails
4. Salve como `email-sequence.md` no diretório atual
5. Após gerar, pergunte: "Quer que eu ajuste o tom, adicione mais e-mails ou crie variações para teste A/B?"
