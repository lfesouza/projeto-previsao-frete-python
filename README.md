# Previsão de Custos de Frete com Machine Learning

## Sobre o Projeto
Este projeto tem como objetivo desenvolver um modelo de regressão capaz de prever o custo total de rotas logísticas antes mesmo do carregamento. Essa ferramenta auxilia no planejamento orçamentário e na previsibilidade de caixa da operação.

## ⚙️ Tecnologias Utilizadas
* **Linguagem:** Python
* **Manipulação de Dados:** Pandas
* **Machine Learning:** Scikit-learn (Regressão Linear)
* **Visualização:** Matplotlib

## 📊 O Dataset
Os dados utilizados simulam uma operação logística real, contendo informações como:
* Distância da rota (km)
* Volume transportado (toneladas)
* Dias de chuva na rota
* Valor de pedágios
* Tempo de carregamento

## 🚀 Resultados
O modelo de Regressão Linear foi treinado com 80% do histórico de viagens e testado com 20% de dados inéditos. 
* **Métrica de Avaliação:** MAE (Mean Absolute Error)
* **Resultado:** O modelo obteve um erro médio de aproximadamente **R$ 236,77**, o que demonstra uma alta capacidade de capturar a regra de precificação, errando apenas o ruído inerente a imprevistos operacionais.

---
*Desenvolvido como parte do portfólio de Ciência de Dados.*
