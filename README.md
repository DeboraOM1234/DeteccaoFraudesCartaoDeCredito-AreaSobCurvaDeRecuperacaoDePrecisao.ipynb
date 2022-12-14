# Detecção de fraudes em cartão de crédito (utilizando área sob curva de recuperação de precisão).ipynb

## É importante que as empresas de cartão de crédito sejam capazes de reconhecer transações fraudulentas com cartão de crédito para que os clientes não sejam cobrados por itens que não compraram.
###### O conjunto de dados foi retirado de: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud. Não foi colocado neste repósitorio por ser demasiadamente grande.
###### Nele, existem transações feitas por **cartões de crédito em setembro de 2013** por titulares de cartões europeus.
###### Este conjunto de dados apresenta transações que ocorreram em dois dias, onde temos **492 fraudes em 284.807 transações**. O conjunto de dados é altamente desequilibrado, a classe positiva (fraudes) responde por 0,172% de todas as transações.
###### Ele **contém apenas variáveis ​​de entrada numéricas que são o resultado de uma transformação PCA**. Características V1, V2, … V28 são os principais componentes obtidos com PCA, as únicas características que não foram transformadas com PCA são 'Tempo' e 'Valor'. 
###### O recurso '**Tempo**' contém os segundos decorridos entre cada transação e a primeira transação no conjunto de dados. O recurso '**Valor**' é o Valor da transação, esse recurso pode ser usado para aprendizado sensível ao custo dependente de exemplo. O recurso '**Class' é a variável de resposta** e assume valor 1 em caso de fraude e 0 caso contrário.
###### Dada a razão de desequilíbrio de classe, utilizou-se ***a Área sob a Curva de Recuperação de Precisão (AUPRC) para medir a precisão***. A precisão da matriz de confusão não é significativa para a classificação desequilibrada.

## A máquina preditiva final obteve 90% de precisão.
