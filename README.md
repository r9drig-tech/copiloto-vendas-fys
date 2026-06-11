# 🍺 IA Aplicada a Vendas — Heineken × DIO

> Repositório completo com os desafios criativos e projeto final do curso  
> **Heineken — Inteligência Artificial Aplicada a Vendas** | DIO

---

## 📁 Estrutura do Repositório

```
copiloto-vendas-fys/
├── README.md
├── desafio-argumentacao-comercial.md
├── desafio-produtividade-pessoal.md
└── knowledge/
    ├── contexto-da-marca.md
    ├── objecoes-comuns.md
    ├── produtos.md
    └── perguntas-frequentes.md
```

---

## 🎯 Desafios Criativos

### 📌 Desafio 1 — Quem Não Vende, Ajuda a Vender! O Poder da Argumentação Comercial com IA

**Ideia:** Roteiros de argumentação para equipes de apoio (promotores, repositores, atendentes) que não são vendedores diretos, mas influenciam a decisão de compra no PDV com as palavras certas.

| | |
|---|---|
| **Público** | Promotores, repositores e atendentes de PDV |
| **Entrega** | Cartão de argumentação: situação → abertura → argumento → encerramento |
| **Diferencial** | Tom humano e natural — sem script engessado, sem pressão de venda |

👉 [`desafio-argumentacao-comercial.md`](./desafio-argumentacao-comercial.md)

---

### 📌 Desafio 2 — Acelerando Sua Produtividade Pessoal com IA

**Ideia:** Painel de prioridades diárias para profissionais com múltiplas frentes simultâneas — projetos técnicos, pós-graduação, portfólio, busca ativa de emprego — usando IA para cortar o ruído e focar no que gera mais resultado no dia.

| | |
|---|---|
| **Público** | Profissionais de dados em transição de carreira |
| **Entrega** | Bloco diário: Top 3 do dia + Fila de valor + Descarte consciente |
| **Diferencial** | Tempo e energia como variáveis reais — sem listas infinitas, sem culpa |

👉 [`desafio-produtividade-pessoal.md`](./desafio-produtividade-pessoal.md)

---

## 🚀 Projeto Final — Copiloto de Vendas FYS

**Tema:** Objeções de Balcão — ajudando representantes comerciais a ativarem padarias e pequenos PDVs com a FYS (refrigerante premium do grupo Heineken).

**Abordagem:** Copiloto baseado em Prompt Engineering com base de conhecimento contextual da marca FYS, construída a partir da live oficial DIO × Heineken.

| | |
|---|---|
| **Usuário principal** | Representante comercial FYS visitando PDVs em campo |
| **Problema resolvido** | Objeções de preço, desconhecimento de marca, falta de espaço na geladeira |
| **Formato** | Prompt reutilizável com variáveis abertas por PDV, objeção e produto |

### 📚 Base de Conhecimento

| Arquivo | Conteúdo |
|---|---|
| [`knowledge/contexto-da-marca.md`](./knowledge/contexto-da-marca.md) | Quem é a FYS, tom, posicionamento e desafios reais |
| [`knowledge/objecoes-comuns.md`](./knowledge/objecoes-comuns.md) | 6 objeções frequentes com contorno e próximo passo |
| [`knowledge/produtos.md`](./knowledge/produtos.md) | Linha FYS, embalagens e dicas de exposição no PDV |
| [`knowledge/perguntas-frequentes.md`](./knowledge/perguntas-frequentes.md) | FAQ para vendedor e consumidor final |

### ✅ Prompt do Copiloto

```
Você é um copiloto de vendas especializado na marca FYS, refrigerante premium do grupo Heineken.
Seu papel é ajudar representantes comerciais a responderem objeções de donos de PDV
(padarias, mercadinhos, lanchonetes) durante visitas em campo.

A FYS tem um tom leve, bem-humorado e sem arrogância. Use esse tom nas respostas.

Contexto da visita:
- Tipo de PDV: [padaria / mercadinho / lanchonete / bar]
- Objeção do cliente: [ex: "não conheço essa marca", "tá caro", "minha geladeira tá cheia"]
- Produto em foco: [ex: FYS Limão 350ml / FYS Tangerina / FYS Maçã]

Gere:
1. Resposta de contorno da objeção — máximo 4 linhas, tom direto e humano
2. Argumento de valor — por que a FYS faz sentido para ESSE tipo de PDV
3. Próximo passo — o que propor para avançar (degustação, mix mínimo, espaço na geladeira)

Evite linguagem corporativa e clichês de vendas.
```

---

## 🛠️ Tecnologias e Conceitos Aplicados

- Prompt Engineering estruturado (papel, contexto, formato, restrições)
- IA Generativa aplicada a processos comerciais reais
- Base de conhecimento contextual para orientar respostas da IA
- Argumentação comercial orientada por valor (não por desconto)

---
## 👤 Autor

**Rodrigo Gonçalves Salgado**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rodrigo--salgado--bi-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/rodrigo-salgado-bi)

---

*Desenvolvido como parte da trilha de IA Generativa — DIO × Heineken*
