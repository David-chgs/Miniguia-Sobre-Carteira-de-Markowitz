# Miniguia-Sobre-Carteira-de-Markowitz
💡 Este repositório faz parte do desafio da DIO sobre uso do NotebookLM como ferramenta de aprendizagem ativa.

# 📚 Miniguia Sobre Carteira de Markowitz (Teoria Moderna do Portfólio)

O material completo está disponível no link abaixo:

👉 [Acessar NotebookLM](https://notebooklm.google.com/notebook/021b2015-6a65-43a9-9fb6-ff19691ce6d1)

## 🎯 Contexto e Objetivos

Este projeto tem como objetivo estudar a **Teoria Moderna do Portfólio**, proposta por Harry Markowitz, com foco na construção de carteiras eficientes a partir da relação entre **risco e retorno**.

A proposta segue o uso do NotebookLM como ferramenta de aprendizado ativo, combinando curadoria de fontes, engenharia de prompts e consolidação do conhecimento.

### Objetivos de estudo:

* Compreender os fundamentos da diversificação de investimentos
* Entender a relação entre risco (variância) e retorno esperado
* Explorar o conceito de fronteira eficiente
* Aplicar conceitos matemáticos em portfólios
* Utilizar IA para aprofundar o aprendizado técnico

---

## 🔎 Curadoria de Fontes

As seguintes fontes abertas foram utilizadas no NotebookLM:

1. Wikipedia – Modern Portfolio Theory
   [Modern portfolio theory](https://en.wikipedia.org/wiki/Modern_portfolio_theory)

2. Wikipedia – Markowitz model
   https://en.wikipedia.org/wiki/Markowitz_model

3. Artigo introdutório sobre teoria de portfólio (Google Scholar)
   https://www.investoetf.com/blog/teoria-moderna-do-portfolio/

4. Tutorial prático de Markowitz com Python
   [analisemacro.com.br](https://analisemacro.com.br/mercado-financeiro/selecao-de-carteira-e-teoria-de-markowitz/)

5. Documentação e exemplos com otimização de portfólio em R
   [RPubs](https://rpubs.com/pradogps/fronteira_eficiente)

---

## 🧠 Engenharia de Prompts e "Cicatrizes"

### 🔹 Prompt 1 (Inicial)

> "Explique a teoria de Markowitz"

**Problema:**
Resposta genérica, sem profundidade prática.

---

### 🔹 Prompt 1 (Refinado)

> "Explique a teoria de Markowitz com exemplos práticos de alocação de ativos"

**Resultado:**
A resposta passou a incluir exemplos e aplicações reais.

---

### 🔹 Prompt 2 (Inicial)

> "O que é risco e retorno?"

**Problema:**
Muito amplo e pouco técnico.

---

### 🔹 Prompt 2 (Refinado)

> "Como risco (variância) e retorno esperado são calculados na teoria de Markowitz?"

**Resultado:**
Trouxe fórmulas matemáticas e maior rigor conceitual.

---

### 🔹 Prompt 3 (Avançado)

> "Como calcular a fronteira eficiente usando Python?"

**Resultado:**
Resposta prática com aplicação em ciência de dados.

---

### 💡 Principais aprendizados com prompts

* Prompts genéricos → respostas superficiais
* Contexto técnico melhora significativamente a qualidade
* Solicitar exemplos práticos aumenta a compreensão
* Especificar ferramentas (Python, dados reais) gera respostas mais úteis

---

## 📘 Miniguia de Estudo

### 📌 1. Resumo Estruturado

A teoria de Markowitz propõe que um investidor pode maximizar retorno esperado para um dado nível de risco através da diversificação.

#### 🔹 Retorno Esperado

E(R_p)=\sum_{i=1}^{n} w_i R_i

O retorno esperado da carteira é a média ponderada dos retornos dos ativos.

---

#### 🔹 Risco da Carteira (Variância)

\sigma_p^2 = \sum_{i=1}^{n}\sum_{j=1}^{n} w_i w_j Cov(R_i, R_j)

O risco considera não apenas os ativos individualmente, mas também a relação entre eles.

---

#### 🔹 Diversificação

A diversificação reduz o risco ao combinar ativos com baixa correlação.

---

#### 🔹 Fronteira Eficiente

Conjunto de carteiras que oferecem o maior retorno possível para cada nível de risco.

---

### 📖 2. Glossário

* **Retorno Esperado** → média ponderada dos retornos
* **Variância** → medida de risco
* **Covariância** → relação entre ativos
* **Correlação** → grau de dependência entre ativos
* **Fronteira Eficiente** → conjunto ótimo de carteiras
* **Diversificação** → estratégia de redução de risco

---

### 🔁 3. Prompts Reutilizáveis

* "Explique [conceito financeiro] com exemplos práticos"
* "Como calcular [métrica] em Python?"
* "Compare [conceito A] e [conceito B]"
* "Gere um passo a passo para construir uma carteira eficiente"
* "Explique como aplicar [conceito] em dados reais"

---

## 💻 Exemplo Prático (Python)

```python
import numpy as np

# retornos esperados de dois ativos
returns = np.array([0.10, 0.12])

# pesos da carteira
weights = np.array([0.5, 0.5])

# retorno esperado do portfólio
portfolio_return = np.dot(weights, returns)

print(portfolio_return)
```

---

## 🚀 Insights Finais

A teoria de Markowitz demonstra que a escolha de ativos não deve ser feita isoladamente, mas sim considerando a interação entre eles.

Esse conceito é altamente relevante em ciência de dados, pois reforça a importância de analisar relações entre variáveis (covariância e correlação), sendo aplicável em modelagem estatística, otimização e análise de risco.

Além disso, o uso do NotebookLM e da engenharia de prompts mostrou-se uma abordagem eficiente para acelerar o aprendizado técnico e estruturar conhecimento de forma reutilizável.

---

## 📎 Como Executar / Reproduzir

1. Revisar os materiais listados nas fontes
2. Explorar os prompts no NotebookLM
3. Testar os exemplos em Python
4. Expandir o estudo com dados reais de mercado

---

## ✍️ Autor

Projeto desenvolvido como parte de um desafio prático da DIO, com foco em aprendizado ativo utilizando IA.
