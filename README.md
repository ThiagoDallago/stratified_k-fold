Stratified Cross Validation

Quer você esteja trabalhando em diagnóstico médico, detecção de fraudes ou qualquer outra tarefa de classificação com dados desbalanceados, a validação cruzada estratificada K-Fold é uma importante técnica
que pode ajudar na melhoria do desempenho do modelo.

O Stratified K-Fold trata-se de uma técnica de validação avançada para conjuntos de dados com uma distribuição desbalanceada de classes.
Garante que cada dobra do conjunto de dados contenha aproximadamente a mesma porcentagem de amostras de cada classe que o conjunto completo.
O desempenho do modelo é avaliado em uma amostra mais representativa de cada classe, mesmo ao lidar com dados desbalanceados.
Isso ajuda a mitigar o viés que pode surgir por ter classes sub-representadas no conjunto de teste e fornece uma estimativa mais confiável do desempenho geral do modelo.

Para fins de estudo, juntamente com a validação cruzada, foi também aplicada o SMOTE, umas das técnicas de oversampling utilizada em machine learning para lidar com conjuntos de dados desbalanceados.
SMOTE (Synthetic Minority Over-sampling Technique) cria novos exemplos sintéticos da classe minoritária, ajudando a equilibrar a distribuição e evitando que o modelo seja dominado pela classe majoritária. 

Importante: A aplicação do SMOTE (Synthetic Minority Over-sampling Technique) deve ser feita apenas no split de treino.

Passos utilizado para a aplicação da validação cruzada juntamento com o SMOTE:
1. Dividir em treino e teste;
2. Aplicar SMOTE no split de treino;
3. Treinar o modelo com dados balanceados;
4. Testar no conjunto original (não balanceado);
5. Avaliar e imprimir resultados.
