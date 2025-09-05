# 🚀 Desafio Lighthouse CD – IMDb  
**Autora:** Nubia Alves

## 📋 Visão Geral  
Este projeto foi desenvolvido como parte do Desafio Lighthouse CD da Indicium. O objetivo é apoiar a escolha do próximo filme a ser produzido pelo estúdio PProductions, utilizando dados do IMDb para gerar insights estratégicos e construir um modelo preditivo capaz de estimar a nota de um filme com base em suas características.

---

## 🎯 Objetivos  
- Realizar limpeza e tratamento dos dados  
- Explorar padrões e relações entre variáveis como nota, bilheteria, duração e gênero  
- Formular hipóteses testáveis com base na análise exploratória  
- Construir um modelo preditivo para estimar a nota IMDb  
- Gerar recomendações estratégicas para futuras produções

---

## 🏗️ Estrutura do Projeto  

```
desafio-lighthouse-cd/
├── eda_imdb.ipynb
├── modelo_imdb.ipynb
├── modelo_imdb.pkl
├── relatorio_interpretativo.pdf
├── requirements.txt
└── README.md
```

## 🛠️ Tecnologias Utilizadas

- Python 3.8+
- Pandas 1.5.3
- NumPy 1.24.2
- Matplotlib 3.7.1
- Scikit-learn 1.2.2
- Joblib 1.2.0
  
---

## 📦 Instalação

Para instalar as dependências necessárias e executar os notebooks localmente, utilize o seguinte comando:

```bash
pip install -r requirements.txt
```

---

## 🚀 Como Executar o Projeto

### 1️⃣ Análise Exploratória

Abra o notebook `eda_imdb.ipynb` e execute as células sequencialmente para:

- Carregar e tratar os dados  
- Visualizar padrões entre nota IMDb, duração, bilheteria e gênero  
- Gerar estatísticas e gráficos que apoiam decisões estratégicas

### 2️⃣ Modelagem Preditiva

Abra o notebook `modelo_imdb.ipynb` para:

- Treinar um modelo de regressão (Random Forest)  
- Avaliar o desempenho com métricas como MSE e R²  
- Salvar o modelo em formato `.pkl` para uso futuro

Para carregar o modelo salvo:

```python
import joblib
modelo = joblib.load('modelo_imdb.pkl')
```

---

## 📊 Métricas de Avaliação

O modelo foi avaliado com os seguintes resultados:

- **MSE (Erro Quadrático Médio):** 0.0351  
- **R² (Coeficiente de Determinação):** 0.5809

---

## 📈 Resultados Esperados

- Previsão da nota IMDb com base em variáveis estruturadas  
- Recomendação de filmes com base em padrões históricos  
- Relatório interpretativo com hipóteses e recomendações estratégicas

---

## 📞 Contato

Para dúvidas ou sugestões:

- **Email:** cantalixto@gmail.com  
- **GitHub:** [Cantalixto](https://github.com/Cantalixto)

⭐ Se este projeto foi útil para você, considere dar uma estrela! ⭐
