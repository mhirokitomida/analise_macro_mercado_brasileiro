# 📊 Análise Macroeconômica do Mercado Acionário Brasileiro

👉 **[🔗 Acesse o Dashboard Interativo (GitHub Pages)](https://mhirokitomida.github.io/analise_macro_mercado_brasileiro/)**

---

## 📌 Sobre o projeto

Este projeto analisa como variáveis macroeconômicas se associam ao comportamento do mercado acionário brasileiro em diferentes níveis:

- 📈 **IBOVESPA** (nível agregado)
- 🏭 **Subsetores**
- 🧾 **Ações individuais**

A proposta é construir um **mapa de sensibilidade macroeconômica**, explorando como diferentes ativos e grupos de ativos respondem, dentro da amostra analisada, a mudanças no ambiente econômico.

---

## 🎯 Objetivo

Investigar perguntas como:

- Quais variáveis macro aparecem mais associadas ao mercado?
- Esse padrão é semelhante para todos os ativos?
- É possível agrupar ativos por perfil macroeconômico?
- A leitura do índice agregado é suficiente para entender o mercado?

---

## 🧠 Variáveis analisadas

- 💵 **Câmbio (Dólar)**
- 📉 **Juros (Selic)**
- 📊 **Inflação (IPCA)**
- 🏭 **Atividade econômica**

> **Observação:** o projeto trabalha com transformações dessas variáveis, como variação do dólar, mudança da Selic, mudança da inflação e proxies de atividade, e não apenas com seus níveis brutos.

---

## ⚙️ Metodologia

O projeto segue um pipeline analítico em etapas:

### 1. 📊 Correlações
Leitura inicial das associações entre variáveis macroeconômicas e retornos.

### 2. ⏳ Defasagens (Lags)
Avaliação de efeitos defasados, buscando capturar relações que podem aparecer com atraso.

### 3. 📉 Regressões
Estimativa de exposições macroeconômicas (betas) para o índice, subsetores e ações.

### 4. 🏆 Rankings
Organização dos ativos e grupos de ativos conforme sua maior sensibilidade observada a cada fator.

### 5. 🔗 Clusterização (KMeans)
Agrupamento de subsetores e ações com perfis macroeconômicos semelhantes.

---

## 🔥 Principais resultados

- O **câmbio** apareceu como uma das variáveis mais associadas ao mercado brasileiro ao longo da amostra  
- A **Selic** ganhou relevância em parte das análises com defasagem  
- Existe forte **heterogeneidade entre ativos e subsetores**  
- O mercado não reage de forma homogênea aos mesmos vetores macroeconômicos  
- A **atividade econômica** apareceu de forma mais difusa após a padronização das exposições  

---

## 🧩 Clusterização

- 🏭 **Subsetores** → **5 clusters**
- 🧾 **Ações** → **7 clusters**

Os clusters representam diferentes combinações de sensibilidade observada a:

- Câmbio  
- Juros  
- Inflação  
- Atividade econômica  

👉 Isso permite uma leitura mais rica do que observar apenas o índice agregado.

---

## ⚡ Key Takeaways

- O mercado brasileiro apresentou forte associação com o **câmbio** dentro da amostra analisada  
- **Juros** ganharam relevância principalmente nas análises com defasagem  
- A análise agregada do índice não captura toda a complexidade do mercado  
- A clusterização ajudou a revelar **perfis distintos de sensibilidade macroeconômica**  
- A atividade econômica não apareceu, em geral, como fator isolado dominante  

---

## 🚀 Diferencial do projeto

Este projeto combina:

- 📊 **Estatística** (correlação e regressão)  
- ⏳ **Modelagem temporal** (lags)  
- 🧠 **Machine Learning** (clusterização)  
- 🖥️ **Visualização interativa** (HTML + GitHub Pages)  

O resultado é um **dashboard interativo voltado à interpretação exploratória do mercado**, conectando evidência quantitativa e leitura econômica.

---

## 🖥️ Dashboard

O projeto inclui um dashboard HTML com:

- análises por nível (**IBOV, subsetores e ações**)
- rankings de sensibilidade macro
- clusters interpretáveis
- tabelas interativas com filtro e ordenação

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

## ⚠️ Observações importantes

- O projeto tem caráter **exploratório**
- Os resultados devem ser interpretados como **associações observadas na amostra**, e não como prova definitiva de causalidade
- A escolha de defasagens foi feita dentro da própria amostra, o que recomenda cautela na generalização dos achados
- As variáveis macro utilizadas representam transformações específicas, e sua leitura econômica deve ser feita com moderação
- A clusterização organiza padrões observados, mas não implica mecanismos causais

---

## 📌 Conclusão

O comportamento do mercado acionário brasileiro não pode ser resumido apenas por uma visão agregada do índice.

Enquanto o **IBOVESPA** oferece uma leitura geral, a análise por **subsetores** e **ações individuais** revela diferentes perfis de sensibilidade macroeconômica, reforçando a heterogeneidade do mercado brasileiro.

A principal contribuição do projeto está em transformar informações macroeconômicas em uma estrutura analítica mais interpretável, útil para:

- melhor leitura de cenário  
- análise mais granular de ativos  
- organização de perfis macroeconômicos semelhantes  

Mais do que oferecer respostas definitivas, o projeto propõe uma forma estruturada de explorar como fatores macro se distribuem de maneira desigual entre diferentes partes do mercado.
