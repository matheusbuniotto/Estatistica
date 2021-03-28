
# Correlação

A correlação é simplesmente uma métrica que mede até que ponto as variáveis ​​(ou recursos ou amostras ou quaisquer grupos) estão associados entre si (positivamente ou negativamente). Em quase todas as análises de dados, os cientistas de dados irão comparar duas variáveis ​​e como elas se relacionam entre si.

A seguir estão as técnicas de correlação mais amplamente utilizadas:

- Covariância
- Coeficiente de correlação de Pearson
- Coeficiente de correlação de classificação de Spearman

### Covariância 
![img](https://miro.medium.com/max/456/0*LM51UdtMMD-5cxKa.png)
A covariância mede a relação linear entre duas variáveis. A covariância é semelhante à correlação entre duas variáveis, no entanto, elas diferem nas seguintes maneiras:

Os coeficientes de correlação são padronizados. Assim, um relacionamento linear perfeito resulta em um coeficiente de correlação 1. A correlação mede tanto a força como a direção da relação linear entre duas variáveis.

Os valores de covariância não são padronizados. Portanto, a covariância pode variar de menos infinito a mais infinito. Assim, o valor para uma relação linear ideal depende dos dados. Como os dados não são padronizadas, é difícil determinar a força da relação entre as variáveis.

É possível utilizar a covariância para compreender a direção da relação entre as variáveis. Valores de covariância positivos indicam que valores acima da média de uma variável estão associados a valores médios acima da outra variável e abaixo dos valores médios são igualmente associado. Valores de covariância negativos indicam que valores acima da média de uma variável estão associados com valores médios abaixo da outra variável.

### Pearson

O coeficiente de correlação de Pearson (r) ou coeficiente de correlação
produto-momento ou o r de Pearson mede o grau da correlação linear entre
duas variáveis quantitativas. É um índice adimensional com valores situados
ente -1,0 e 1.0 inclusive, que reflete a intensidade de uma relação linear entre
dois conjuntos de dados.
![img](https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/Correlation_coefficient.png/400px-Correlation_coefficient.png)

Este coeficiente, normalmente representado pela letra "r" assume apenas
valores entre -1 e 1.

- r= 1 Significa uma correlação perfeita positiva entre as duas variáveis.

- r= -1 Significa uma correlação negativa perfeita entre as duas variáveis - Isto é, se uma aumenta, a outra sempre diminui.
  
- r= 0 Significa que as duas variáveis não dependem linearmente uma da outra.
No entanto, pode existir uma outra dependência que seja "não linear". Assim, o
resultado r=0 deve ser investigado por outros meios


### Spearman
![img](https://assets.datacamp.com/production/repositories/4371/datasets/0620bcd29b194d576ee6399b51223fef6994a433/spearmannHW.png)

O coeficiente de correlação de postos de Spearman, denominado pela letra
grega ρ (rho), é uma medida de correlação não-paramétrica. Ao contrário do
coeficiente de correlação de Pearson <b>não requer a suposição que a relação
entre as variáveis é linear, nem requer que as variáveis sejam quantitativas</b>;
pode ser usado para as variáveis medidas no nível ordinal. 


[Correalação - UFSC](https://www.inf.ufsc.br/~vera.carmo/Correlacao/Correlacao_Pearson_Spearman_Kendall.pdf)
