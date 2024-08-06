# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

## 📋 Introdução:

- Este projeto foi desenvolvido usando o SageMaker Canvas como parte do Bootcamp Nexa - Machine Learning para Iniciantes na AWS da DIO.

## 🚀 Passo a Passo

### 1. Selecionando o Dataset.

-  O Dataset escolhido foi o "Perifericos.csv", um dataset fictício criado especificamente para este projeto de previsão de estoque.
  
-  Este dataset inclui dados sobre diferentes tipos de periféricos, como mouses, teclados, headsets, processadores, entre outros itens, bem como suas respectivas marcas, modelos, preços, quantidades em estoque e classificações.
   
-  Essas informações serão usadas  para treinar e testar o modelo de previsão de estoque no Amazon SageMaker Canvas.

### 2. Construindo/Treinando.

- A coluna escolhida como Alvo da previsão é a Tipo.

- As colunas que fornecerão as informações sobre os periféricos e que serão usadas para fazer as previsões são:
  
- Quantidade.
  
- Preço.
  
- Modelo.
  
- Marca.
  
- Classificação.

### 3. Analisando o Dataset.

- Acurácia: O modelo de previsão tem 80% de previsões corretas, com uma taxa de erro de 20%. Isso indica que, embora o modelo esteja realizando previsões corretas na maioria das vezes, ainda há uma margem para melhorias.

- Contribuição das Variáveis:

- Modelo: A variável Modelo tem uma contribuição significativa para a previsão do tipo de periférico, com cerca de 44%. Isso sugere que a especificação do modelo é um dos principais fatores que influenciam a escolha do tipo de periférico, indicando que muitas pessoas consideram o modelo como um fator decisivo na compra.

- Preço: A variável Preço contribui com aproximadamente 39% para as previsões. Isso reforça a ideia de que o preço é um fator importante na classificação dos periféricos, mostrando que os consumidores frequentemente consideram o preço ao escolher um periférico.

- Marca: A variável Marca tem uma contribuição menor, em torno de 17%. Isso sugere que, embora a marca ainda seja um fator relevante, ela tem uma influência menor em comparação com o modelo e o preço.

### 4. Conclusão.

- Após o treinamento e ajuste do modelo, você pode utilizá-lo para prever o tipo de periférico. No Amazon SageMaker Canvas, faça isso carregando um novo conjunto de dados que inclua as variáveis preditivas: Quantidade, Preço, Modelo, Marca e Classificação.
  
- Usando o modelo, você poderá identificar quais fatores são mais influentes na decisão de compra dos clientes, como o preço, o modelo ou a marca do periférico. Isso ajudará a entender melhor as preferências dos seus clientes.


