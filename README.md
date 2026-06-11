# 🥤 Copiloto de Vendas FYS — IA para Atendimento ao Cliente

> Projeto Final do Bootcamp **Heineken — Inteligência Artificial Aplicada a Vendas** | DIO  
> Tema escolhido: **"Objeções de Balcão"** — ajudando vendedores a ativarem padarias e pequenos PDVs com a FYS

**Autor:** Rodrigo Gonçalves Salgado  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rodrigo--salgado--bi-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/rodrigo-salgado-bi)
[![GitHub](https://img.shields.io/badge/GitHub-r9drig--tech-181717?style=flat&logo=github)](https://github.com/r9drig-tech)

---

## 🎯 Tema Escolhido

**Objeções de Balcão** — A FYS enfrenta um desafio real: é uma marca relativamente nova no mercado de refrigerantes premium dentro do portfólio Heineken, e muitos donos de PDV (padarias, lanchonetes, mercados de bairro) hesitam em aceitar o produto por objeções comuns como preço, desconhecimento da marca, medo de baixo giro ou fidelidade a marcas já estabelecidas.

Este projeto propõe um **copiloto de IA** que ajuda o representante de vendas a responder essas objeções com argumentos precisos, humanizados e alinhados ao tom da marca FYS — leve, bem-humorado e sem forçar.

---

## 👤 Usuário Principal

**Representante comercial da FYS / Heineken** visitando pontos de venda (padarias, mercadinhos, lanchonetes) em campo.

Perfil: profissional com alta demanda de visitas diárias, pouco tempo por PDV e necessidade de respostas rápidas e contextualizadas para cada tipo de objeção e perfil de estabelecimento.

---

## 🔧 Problema que a Solução Resolve

| Situação real | Dor do vendedor |
|---|---|
| Dono da padaria diz "não conheço essa marca" | Não sabe como apresentar a FYS de forma rápida e convincente |
| Cliente diz "tá caro demais" | Não tem argumento de valor pronto, cede ao desconto |
| PDV diz "já tenho Guaraná Antarctica" | Não sabe como posicionar a FYS como complemento, não concorrente |
| Geladeira cheia, sem espaço | Não sabe sugerir qual produto retirar ou como negociar espaço |

O copiloto resolve isso entregando, em segundos, o argumento certo para cada situação — baseado no contexto real da marca.

---

## 🤖 Abordagem Usada

**Copiloto de vendas baseado em Prompt Engineering com base de conhecimento contextual.**

A solução não é um app nem um chatbot completo — é um **sistema de prompts estruturados** que qualquer vendedor pode usar via ChatGPT, Claude ou outra IA generativa, alimentado por uma base de conhecimento da marca FYS.

Estrutura:
```
copiloto-vendas-fys/
├── README.md
└── knowledge/
    ├── contexto-da-marca.md
    ├── objecoes-comuns.md
    ├── produtos.md
    └── perguntas-frequentes.md
```

---

## 📚 Base de Conhecimento Utilizada

A base de conhecimento foi construída a partir de:
- **Transcrição da live FYS: Por Dentro da Marca, Desafios e Ideias para o Projeto Final** (fonte oficial DIO/Heineken)
- Repositório de apoio: [digitalinnovationone/copiloto-vendas-ia-atendimento-cliente-fys](https://github.com/digitalinnovationone/copiloto-vendas-ia-atendimento-cliente-fys)

Os arquivos em `/knowledge` sintetizam as informações mais relevantes para o copiloto funcionar com contexto real.

---

## ✅ Prompt do Copiloto

```
Você é um copiloto de vendas especializado na marca FYS, refrigerante premium do grupo Heineken.
Seu papel é ajudar representantes comerciais a responderem objeções de donos de PDV
(padarias, mercadinhos, lanchonetes) durante visitas em campo.

A FYS tem um tom leve, bem-humorado e sem arrogância. Ela não tenta ser a número 1 —
ela quer ser a mais gostosa na sua categoria. Use esse tom nas respostas.

Contexto da visita:
- Tipo de PDV: [padaria / mercadinho / lanchonete / bar]
- Objeção do cliente: [descreva aqui — ex: "não conheço essa marca", "tá caro", "minha geladeira tá cheia"]
- Produto em foco: [ex: FYS Limão 350ml / FYS Tangerina / FYS Maçã]

Gere:
1. Resposta de contorno da objeção — máximo 4 linhas, tom direto e humano
2. Argumento de valor — por que a FYS faz sentido para ESSE tipo de PDV
3. Próximo passo — o que propor para avançar (degustação, mix mínimo, espaço na geladeira)

Evite: linguagem corporativa, clichês de vendas e qualquer coisa que soe como script robótico.
Fale como um bom vendedor que acredita no produto e quer genuinamente ajudar o dono do PDV.
```

---

## 💬 Exemplo de Conversa Gerada

**Entrada:**
- PDV: padaria de bairro
- Objeção: "Nunca ouvi falar dessa FYS. Não sei se vai vender."
- Produto: FYS Limão 350ml

**Resposta do Copiloto:**

> **Contorno da objeção:**
> "Faz sentido, é uma marca nova por aqui mesmo. Mas ela já chegou em outros pontos da região e está girando bem — especialmente de tarde, quando o pessoal quer algo diferente do de sempre."
>
> **Argumento de valor:**
> "A FYS é do grupo Heineken, então tem estrutura de reposição garantida e não some da prateleira. Para uma padaria como a sua, ela entra bem no horário do lanche e do café da tarde — cliente que quer uma opção mais especial sem pagar o preço de um suco premium."
>
> **Próximo passo:**
> "Que tal a gente testar com 12 unidades essa semana? Coloca na geladeira perto do balcão e vê o movimento. Se não girar em 15 dias, a gente revê juntos. Risco zero pra você."

---

## 🚀 Possíveis Melhorias Futuras

- Integrar o copiloto a um bot de WhatsApp para uso direto em campo pelo celular
- Criar um painel de métricas com os tipos de objeção mais frequentes por região
- Adicionar módulo de **priorização de PDVs** com base em potencial de giro estimado
- Treinar um modelo fine-tuned com histórico real de conversas de vendedores FYS
- Expandir a base de conhecimento com dados de sell-out por tipo de estabelecimento

---

*Projeto desenvolvido como entrega do Bootcamp Heineken — Inteligência Artificial Aplicada a Vendas | DIO*  
*Base de conhecimento construída a partir da live oficial FYS × DIO*
