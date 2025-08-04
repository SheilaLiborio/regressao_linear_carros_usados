# 🚗 Análise Preditiva de Preço de Veículos Usados

Projeto desenvolvido como parte de um desafio de análise de dados, com foco em entender quais variáveis mais influenciam o **preço de venda** de veículos usados.

---

## 🎯 Objetivo

Auxiliar uma empresa de revenda de veículos usados na **precificação adequada** dos automóveis. O modelo busca identificar os fatores que mais impactam o valor de venda, prevenindo perdas financeiras e otimizando as vendas.

---

## 🗃️ Sobre o Conjunto de Dados

O dataset `desafio_carros_usados.csv` contém dados de veículos vendidos ao longo dos últimos anos.

### 📑 Principais colunas:
- `id`: Identificador único
- `make`: Marca
- `model`: Modelo
- `year`: Ano de fabricação
- `price`: Preço de venda (variável alvo)
- `mileage`: Quilometragem
- `engine_size`: Tamanho do motor
- `fuel_type`: Tipo de combustível
- `transmission`: Tipo de transmissão
- `doors`: Número de portas
- `color`: Cor
- `tax`: Taxa anual de imposto
- `mpg`: Eficiência de combustível (Milhas por Galão)
- `sold_date`: Data de venda

---

## 🔍 Etapas do Projeto

### 1. Análise de Correlação
- Cálculo das correlações entre as variáveis numéricas e `price`
- Identificação das variáveis com maior e menor impacto sobre o preço

### 2. Foco nas 5 Variáveis Mais Correlacionadas
Para cada uma delas:
- 📊 Histograma e boxplot
- 📈 Gráfico de dispersão (scatterplot) com `price` no eixo Y
- 📉 Regressão linear simples
- Interpretação dos **coeficientes** e do **R²**

---

## 🧰 Tecnologias Utilizadas

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (para regressão linear)

---

## 📌 Resultados Esperados

- Compreensão clara das variáveis mais determinantes no valor de um carro usado
- Visualizações que auxiliam na leitura dos dados
- Modelos simples, mas interpretáveis, para apoio à tomada de decisão na precificação

---

## 👩‍💻 Autora

**Sheila Liborio**  
Engenheira e entusiasta de dados, com foco em análise preditiva e geração de valor a partir de dados reais.  
[LinkedIn](https://www.linkedin.com/in/sheilaliborio)

---

## ⚠️ Aviso

Este projeto é educacional e os resultados não devem ser aplicados diretamente em decisões comerciais reais sem validação adicional.
