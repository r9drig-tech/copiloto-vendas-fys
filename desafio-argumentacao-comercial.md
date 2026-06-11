# 🍺 Desafio Criativo — Quem Não Vende, Ajuda a Vender! O Poder da Argumentação Comercial com IA

**Autor:** Rodrigo Gonçalves Salgado  
**Curso:** Heineken — Inteligência Artificial Aplicada a Vendas | DIO  
**GitHub:** [github.com/r9drig-tech](https://github.com/r9drig-tech)

---

## 🧱 Passo 1 — Definindo a Intenção

> **Modelo:** Quero que a IA gere [tipo de conteúdo] para [público], com o objetivo de [resultado].

**Minha resposta:**

Quero que a IA gere **roteiros de argumentação comercial** para equipes de apoio (promotores, repositores e atendentes de PDV) que não são vendedores diretos, com o objetivo de **transformar qualquer interação no ponto de venda em uma oportunidade de influenciar positivamente a decisão de compra do consumidor final**, sem que a abordagem pareça uma venda forçada.

---

## 🧱 Passo 2 — Contexto e Restrições

> **Modelo:** Considere o seguinte contexto: [contexto]. O conteúdo deve ter [formato]. Evite [o que evitar].

**Minha resposta:**

Considere o seguinte contexto: nem todo colaborador que está no PDV tem função de vendedor — mas todos influenciam a experiência do consumidor. Um promotor que organiza a gôndola, um repositor que conversa com o dono do bar ou um atendente que responde uma dúvida sobre produto podem, com as palavras certas, aumentar a venda sem parecer que estão "vendendo". O foco é em argumentos naturais, baseados em benefícios reais do produto (sabor, ocasião, experiência) e no contexto do consumidor (celebração, happy hour, refeição, presente).

O conteúdo deve ter formato de **cartão de argumentação** com quatro campos: situação, frase de abertura, argumento principal e encerramento — curto o suficiente para ser memorizado ou consultado rapidamente no celular durante a visita.

Evite linguagem de vendas forçada, termos de marketing corporativo e qualquer abordagem que pareça script engessado ou pressão de compra.

---

## 🧱 Passo 3 — Prompt Final

---

### ✅ Prompt Final

```
Você é um especialista em argumentação comercial para o setor de bebidas.
Seu papel é criar roteiros simples e naturais para colaboradores de apoio em pontos
de venda (promotores, repositores, atendentes) — pessoas que não têm função de vendedor,
mas que interagem diariamente com donos de PDV e consumidores finais.

Contexto da situação:
- Perfil do colaborador: [promotor / repositor / atendente de balcão]
- Situação: [ex: consumidor olhando para a gôndola / dono do bar perguntando qual produto vende mais / cliente em dúvida entre duas marcas]
- Produto em foco: [ex: FYS Limão 350ml / Heineken Long Neck / Amstel Lata]

Gere um cartão de argumentação com:
1. 📍 Situação — descrição resumida do momento (1 linha)
2. 💬 Frase de abertura — como iniciar a conversa de forma natural, sem parecer que está vendendo
3. 🎯 Argumento principal — benefício real do produto ligado à ocasião ou ao perfil do consumidor (máximo 3 linhas)
4. ✅ Encerramento — frase leve que convida à decisão sem pressionar

Tom: humano, leve e confiante. Fale como alguém que conhece o produto e quer genuinamente
ajudar — não como um vendedor batendo meta.
```

---

## 💡 Por que este prompt é eficaz?

| Elemento | Impacto |
|---|---|
| **Papel bem definido** | A IA entende que o foco é em quem *apoia*, não em quem *vende* |
| **Situação variável** | O prompt vira uma ferramenta reutilizável para diferentes contextos de PDV |
| **Formato de cartão** | Saída curta e memorizável — prática para uso real em campo |
| **Tom humanizado** | Evita o estereótipo do "vendedor chato", tornando a abordagem mais eficaz |

---

## 🥤 Exemplo de uso real

**Entrada:**
- Colaborador: promotor
- Situação: consumidor olhando para a gôndola de refrigerantes, hesitante entre FYS e outra marca
- Produto: FYS Tangerina 350ml

**Saída esperada da IA:**

> **📍 Situação:** Consumidor na gôndola comparando FYS Tangerina com outro refrigerante.
>
> **💬 Abertura:** "Essa FYS Tangerina é novidade — você já experimentou?"
>
> **🎯 Argumento:** "É do grupo Heineken, mas com um sabor bem diferente do que já existe por aí. Tangerina não tem concorrente direto na geladeira — quem experimenta uma vez sempre volta. Fica ótima gelada, especialmente no lanche da tarde."
>
> **✅ Encerramento:** "Vale a pena levar uma pra conhecer. Se não gostar, é só não repetir — mas todo mundo que provou gostou."

---

*Desafio entregue como parte do curso Heineken — Inteligência Artificial Aplicada a Vendas | DIO*
