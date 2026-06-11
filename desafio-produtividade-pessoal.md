# ⚡ Desafio Criativo — Acelerando Sua Produtividade Pessoal com IA

**Autor:** Rodrigo Gonçalves Salgado  
**Curso:** Heineken — Inteligência Artificial Aplicada a Vendas | DIO  
**GitHub:** [github.com/r9drig-tech](https://github.com/r9drig-tech)

---

## 🧱 Passo 1 — Definindo a Intenção

> **Modelo:** Quero que a IA gere [tipo de conteúdo] para [público], com o objetivo de [resultado].

**Minha resposta:**

Quero que a IA gere um **painel de prioridades diárias** para profissionais de dados e BI que acumulam múltiplas frentes simultâneas — projetos técnicos, pós-graduação, portfólio no GitHub, busca ativa de emprego e estudos de novas tecnologias — com o objetivo de **reduzir a sobrecarga cognitiva, focar no que gera mais resultado no dia e eliminar o tempo perdido decidindo o que fazer a seguir**.

---

## 🧱 Passo 2 — Contexto e Restrições

> **Modelo:** Considere o seguinte contexto: [contexto]. O conteúdo deve ter [formato]. Evite [o que evitar].

**Minha resposta:**

Considere o seguinte contexto: o profissional trabalha durante o dia, estuda à noite e nos fins de semana, e tem uma lista mental de tarefas que nunca para de crescer. Ele precisa equilibrar entregas de curto prazo (submissões na DIO, candidaturas a vagas) com investimentos de longo prazo (projetos de portfólio, certificações, aprendizado de novas ferramentas como Airflow, dbt e Databricks). A energia e o foco variam ao longo do dia — tarefas pesadas de manhã, revisões leves à noite.

O conteúdo deve ter formato de **bloco diário estruturado**, com três seções: (1) Top 3 do dia — o que não pode deixar de fazer, (2) Fila de valor — o que avança mais a carreira se houver tempo, (3) Descarte consciente — o que pode esperar sem culpa.

Evite listas intermináveis, linguagem motivacional vazia e qualquer sugestão que ignore o limite real de horas disponíveis.

---

## 🧱 Passo 3 — Prompt Final

---

### ✅ Prompt Final

```
Você é um assistente de produtividade para profissionais de dados em transição de carreira.
Seu papel é ajudar a organizar o dia de forma realista, priorizando o que gera mais resultado
com o tempo e energia disponíveis — sem listas infinitas e sem culpa.

Contexto do profissional:
- Trabalha durante o dia (disponibilidade de estudo: noite e fins de semana)
- Frentes ativas: [ex: desafio DIO, portfólio GitHub, candidaturas, pós-graduação, estudo de Airflow]
- Energia do dia: [alta / média / baixa]
- Tempo disponível hoje: [ex: 1h30]

Com base nessas informações, gere um bloco diário com:

1. 🎯 Top 3 do Dia — as 3 tarefas que não podem ficar para amanhã (com tempo estimado cada)
2. 📈 Fila de Valor — 2 tarefas que mais avançam a carreira se houver tempo sobrando
3. 🗑️ Descarte Consciente — 1 ou 2 itens que podem esperar sem impacto real hoje

Regras:
- O total de tempo do Top 3 não pode ultrapassar o tempo disponível informado
- Seja direto: nome da tarefa + tempo estimado + por que é prioridade hoje
- Evite motivação vazia. Fale como um colega sênior que respeita o tempo do outro.
```

---

## 💡 Por que este prompt funciona?

| Elemento | Impacto |
|---|---|
| **Energia como variável** | A IA ajusta a dificuldade das tarefas ao estado real do dia |
| **Tempo como restrição dura** | Impede sugestões irreais — o Top 3 cabe no tempo disponível |
| **Descarte consciente** | Elimina a culpa de não fazer tudo — foco é uma escolha, não falha |
| **Tom de colega sênior** | Resposta direta, sem paternalismo motivacional |

---

## 📋 Exemplo de uso real

**Entrada:**
- Frentes: desafio DIO (prazo amanhã), candidatura para vaga de Data Engineer, estudo de dbt
- Energia: média
- Tempo disponível: 1h30

**Saída esperada da IA:**

> **🎯 Top 3 do Dia**
> 1. Finalizar e submeter desafio DIO — 45 min → prazo amanhã, não dá pra adiar
> 2. Revisar e enviar candidatura para vaga Data Engineer — 20 min → janela de oportunidade aberta agora
> 3. Atualizar README do projeto no GitHub — 15 min → reforça o portfólio que o recrutador vai ver
>
> **📈 Fila de Valor (se sobrar tempo)**
> 1. Assistir primeira aula de dbt — 30 min → investimento de longo prazo na transição
>
> **🗑️ Descarte Consciente**
> - Estudar Airflow hoje → energia média não combina com conteúdo pesado novo; deixa para o fim de semana

---

*Desafio entregue como parte do curso Heineken — Inteligência Artificial Aplicada a Vendas | DIO*
