# **Previsão de Preços de Apartamentos em São Paulo**

Este projeto utiliza técnicas de Machine Learning para prever os preços de apartamentos na cidade de São Paulo. Ele inclui análises exploratórias e a construção de modelos preditivos baseados em dados reais, considerando características dos imóveis, como área, número de quartos, banheiros, vagas de garagem e localização.

---

## **Estrutura do Projeto**

- **data/**: Contém os dados utilizados no projeto.
- **notebook/**: Contém o notebook Jupyter com as análises e a construção dos modelos preditivos.

---

## **Tecnologias e Pré-requisitos**

- **Python 3.9+**
- Bibliotecas utilizadas:
  - `warnings`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

---

## **Contexto da Análise**

A análise se concentra em identificar os principais fatores que influenciam os preços de apartamentos na cidade de São Paulo e construir um modelo preditivo eficiente. A abordagem inclui:
- **Análise Exploratória**: Visualizações e estatísticas descritivas para compreender os padrões nos dados.
- **Construção de Modelos**: Teste de diferentes algoritmos de regressão (Linear Regression, Decision Tree, Random Forest).
- **Otimização de Hiperparâmetros**: Ajuste fino do modelo Random Forest utilizando GridSearchCV para melhorar o desempenho preditivo.

Com essas análises, foi possível identificar que fatores como localização, área, número de quartos e vagas de garagem têm grande impacto nos preços, com o modelo Random Forest explicando cerca de **59% da variabilidade nos preços**.


---

## **Como Executar**

1. Clone este repositório:
     ```bash
     git clone https://github.com/Suerdo/Apartment_Price_Forecast_SP.git
2. Navegue até o diretório do projeto:
    ```bash
    cd Apartment_Price_Forecast_SP
3. Abra e execute o notebook Jupyter:
    ```bash
    jupyter notebook notebooks/apartment_price_analysis.ipynb



