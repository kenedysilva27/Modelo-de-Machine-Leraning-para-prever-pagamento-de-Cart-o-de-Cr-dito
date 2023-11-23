Modelo para prever não pagamento de Cartão de Crédito
Este é um projeto em que uso Machine Learning com o algoritmo de árvore de decisão para prever o não pagamento de cartão de crédito.

Os dados são públicos, trata-se do conjunto de dados Taiwan extraído do Kaggle.

Como o algoritmo funciona?

Uma árvore de decisão é um modelo de aprendizagem de máquina que toma decisões com base em uma série de condições. Ela funciona como um fluxograma, onde cada nó interno representa uma condição sobre uma característica dos dados, cada ramo representa o resultado dessa condição, e cada folha representa a decisão final ou a previsão.

Como o projeto foi feito?

Foi aplicada uma árvore de decisão ao conjunto de dados Taiwan_Dataset para prever se um cliente irá ou não pagar o cartão de crédito no próximo mês. As características (ou características) utilizadas na decisão incluíram EDUCATION, PAY_0, PAY_2, PAY_3, PAY_4, PAY_5, PAY_6 e AGE. O processo de treinamento da árvore de decisão envolve ajustar o modelo aos dados, encontrando as condições e divisões ideais para fazer variações.

Após o treinamento, o modelo foi avaliado com métricas de desempenho, como acurácia, precisão, recall e pontuação F1. Essas análises fornecem insights sobre a capacidade do modelo de identificar corretamente os clientes que pagam ou não o cartão de crédito.

Dificuldades do modelo

O modelo encontrou dificuldades na classificação dos pagamentos (1).

Bibliotecas utilizadas: Pandas,Numpy,Matplotlib,Seaborn e sklearn
