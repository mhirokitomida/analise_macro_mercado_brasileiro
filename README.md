# 📊 Análise Macroeconômica do Mercado Acionário Brasileiro

👉 **[🔗 Acesse o Dashboard Interativo (GitHub Pages)](https://mhirokitomida.github.io/analise_macro_mercado_brasileiro/)**

---

## 📌 Sobre o projeto

Este projeto analisa como variáveis macroeconômicas impactam o mercado acionário brasileiro em diferentes níveis:

- 📈 IBOVESPA (nível agregado)
- 🏭 Subsetores
- 🧾 Ações individuais

A proposta é construir um **mapa de sensibilidade macroeconômica**, mostrando como diferentes ativos reagem a mudanças no ambiente econômico.

---

## 🎯 Objetivo

Responder perguntas como:

- Quais variáveis macro mais influenciam o mercado?
- O impacto é igual para todos os ativos?
- É possível agrupar ativos por perfil macroeconômico?

---

## 🧠 Variáveis analisadas

- 💵 **Câmbio (Dólar)**
- 📉 **Juros (Selic)**
- 📊 **Inflação (IPCA)**
- 🏭 **Ciclo Econômico (Atividade)**

---

## ⚙️ Metodologia

O projeto segue um pipeline completo:

### 1. 📊 Correlações
Análise inicial das relações entre macro e retornos

### 2. ⏳ Defasagens (Lags)
Captura do efeito atrasado das variáveis macro

### 3. 📉 Regressões
Estimativa dos betas de sensibilidade macroeconômica

### 4. 🏆 Rankings
Identificação dos ativos mais sensíveis a cada fator

### 5. 🔗 Clusterização (KMeans)
Agrupamento por perfil macroeconômico

---

## 🔥 Principais resultados

- O **câmbio** é um dos principais drivers do mercado brasileiro  
- A **Selic** ganha relevância quando analisada com defasagem  
- Existe forte **heterogeneidade entre ativos**  
- O mercado não reage de forma uniforme  
- A **atividade econômica** apresenta efeito mais difuso após padronização  

---

## 🧩 Clusterização

- 🏭 Subsetores → **5 clusters**
- 🧾 Ações → **7 clusters**

Os clusters representam diferentes combinações de sensibilidade a:

- Câmbio  
- Juros  
- Inflação  
- Ciclo econômico  

👉 Isso permite uma análise muito mais rica do que olhar apenas o índice agregado.

---

## ⚡ Key Takeaways

- O mercado brasileiro é fortemente influenciado pelo **câmbio**  
- **Juros atuam com defasagem**, não de forma imediata  
- A análise agregada esconde a complexidade do mercado  
- A clusterização revela **perfis estruturais de ativos**  
- A atividade econômica não aparece como fator isolado dominante  

---

## 🚀 Diferencial do projeto

Este projeto combina:

- 📊 Estatística (correlação e regressão)  
- ⏳ Modelagem temporal (lags)  
- 🧠 Machine Learning (clusterização)  
- 🖥️ Visualização interativa (HTML + GitHub Pages)  

O resultado é um **dashboard interativo com interpretação econômica clara**.

---

## 🖥️ Dashboard

O projeto inclui um dashboard HTML com:

- Análises por nível (IBOV, subsetores, ações)
- Rankings de sensibilidade macro
- Clusters interpretáveis
- Tabelas interativas com filtro e ordenação

👉 **[Acesse aqui](https://mhirokitomida.github.io/analise_macro_mercado_brasileiro/)**

---

## 🛠️ Tecnologias utilizadas

- Python  
- pandas  
- numpy  
- statsmodels  
- scikit-learn  
- matplotlib  
- HTML + CSS + JavaScript  

---

## 📌 Conclusão

O comportamento do mercado acionário brasileiro não pode ser explicado apenas por uma visão agregada.

Enquanto o IBOV oferece uma visão geral, a análise por subsetores e ações revela diferentes perfis de sensibilidade macroeconômica.

A principal contribuição do projeto é transformar dados macroeconômicos em uma estrutura interpretável, permitindo:

- melhor análise de cenário  
- construção de portfólio mais informada  
- identificação de oportunidades  
