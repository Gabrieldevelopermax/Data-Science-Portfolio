### [ Detecção de Fraudes em Transações com Cartão de Crédito ](https://github.com/Gabrieldevelopermax/Data-Science-Portfolio/blob/main/Projeto%203-%20Detec%C3%A7%C3%A3o%20de%20Fraudes%20em%20Transa%C3%A7%C3%B5es%20com%20Cart%C3%A3o%20de%20Cr%C3%A9dito/Prevenindo_Fraudes_de_Cart%C3%A3o_de_Cr%C3%A9dito_com_Machine_Learning.ipynb) :credit_card:

  

  

![Image header](../Fotos/fraude-cartao-de-credito.jpg)



É importante que as empresas de cartão de crédito sejam capazes de reconhecer transações fraudulentas com cartão de crédito para que os clientes não sejam cobrados por itens que não compraram.

O conjunto de dados contém transações feitas por cartões de crédito em setembro de 2013 por titulares de cartões europeus.  
Este conjunto de dados apresenta transações ocorridas em dois dias, onde temos 492 fraudes em 284.807 transações. O conjunto de dados é altamente desbalanceado, a classe positiva (fraudes) responde por 0,172% de todas as transações.

Ele contém apenas variáveis ​​de entrada numéricas que são o resultado de uma transformação PCA. Infelizmente, devido a questões de confidencialidade, não podemos fornecer os recursos originais e mais informações básicas sobre os dados. As características V1, V2, … V28 são os principais componentes obtidos com PCA, as únicas características que não foram transformadas com PCA são 'Time' e 'Amount'. O recurso 'Tempo' contém os segundos decorridos entre cada transação e a primeira transação no conjunto de dados. O recurso 'Valor' é o valor da transação, esse recurso pode ser usado para aprendizado sensível ao custo dependente de exemplo. A característica 'Classe' é a variável de resposta e assume valor 1 em caso de fraude e 0 caso contrário.

Dada a taxa de desequilíbrio de classe, recomendamos medir a precisão usando a Área sob a Curva de Rechamada de Precisão (AUPRC). A precisão da matriz de confusão não é significativa para a classificação desbalanceada.

  

Fonte: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

  

  

## Bibliotecas utilizadas

  

Pandas | Numpy | Sklearn | Matplotlib

  

  
  

## Conjunto de dados

  
Amount - Valor da transação
Time- Número de segundos decorridos entre esta transação e a primeira transação no conjunto de dados
Class- 1 (fraude) - 0 (Verdadeira)
V1 V28- Atributos transformados em PCA