# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao meu desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Usaremos o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML).
## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

## 🚀 Passo a Passo

### 1. Selecionando o Dataset

-   Ao navegar na pasta `datasets` deste repositório. Foi escolhido um dataset predefinido como `dataset-1000-xom-preco-promocional-e-renovacao-estoque.csv`.
-   Apos a escolha do dataset realizei o upload do arquivo no SageMarker Canvas.

### 2. Construção/Treinamento

-   Ao abrir o SageMaker Canvas, importei o dataset escolhido para analise.
-   Configurei as variáveis de entrada e saída de acordo com os dados apresentados.
-   Iniciei o treinamento do modelo.

### 3. Analise

-   Após a conclusão do treinamento, as métricas apresentadas foram 0.381 Avg.wQL / 0.444 MAPE / 0.549 WAPE / 25.688 RMSE / 0.576 MASE.
-   As principais características que influenciaram as previsões se deu pelos feriados BR, que influenciaram cerca de 12.68% nos dados.

### 4. Previsão

-   Depois do modelo ser treinado, é o momento em que realizamos a previsão de estoque.
-   Ao exportar os resultados podemos perceber que a previsão os produtos tendem com o tempo ter seus estoques diminuídos, e com a diminuição do preço, os estoques aumentam e consequentemente as vendas também. Com variações neutras positivas e negativas, caso o produto não venda como esperado.
-   Todas as previsões apresentam um preço adicional mais barato que o original, para ter ciência de como seria seu desempenho caso o produto esteja com desconto.
