
# Dispersão

Descrever o quão semelhante ou variado o conjunto de valores observados é para uma determinada variável.

### Amplitude

Em um conjunto de informações numéricas, a primeira medida de tendência central é chamada amplitude e é obtida a partir da diferença entre a maior informação da lista e a menor.

### Quartis

Uma outra forma de sumarizar dados é em termos dos quantis ou percentis. Essas medidas são particularmente úteis para dados não simétricos.

A mediana (ou percentil 50) é definida como o valor que divide os dados ordenados ao meio.

Adicionalmente, <b> os quartis inferior e superior, Q1 e Q3, são definidos como os valores abaixo dos quais estão um quarto e três quartos</b>, respectivamente, dos dados.

Estes três valores são frequentemente usados para resumir os dados juntamente com o mínimo e o máximo.

Eles são obtidos ordenando os dados do menor para o maior, e então conta-se o número apropriado de observações: ou seja é   $ \frac{n+1}{4}$, $ \frac{n+1}{2}$ e $ \frac{3(n+1)}{4}$     para o quartil inferior, mediana e quartil superior, respectivamente.


A medidade de dispersão é a <b>amplitude inter-quartis, IQR $ =$ Q3 $ -$ Q1, i.e. é a diferença entre o quartil superior e o inferior. </b>

Exemplo. O número de crianças em 19 famílias foi

0, 1, 1, 2, 2, 2, 2, 2, 3, 3, 3, 4, 4, 5, 6, 6, 7, 8, 10
A mediana é o (19+1) / 2 = $ 10^{o}$ valor, i.e. 3 crianças.

O quartil inferior e superior são os valores $ 5^{o}$ e $ 15^{o}$, i.e. 2 e 6 crianças, portanto amplitude inter-quartil é de 4 crianças. Note que 50% dos dados estão entre os quartis inferior e superior.


#### Box-and-Whisker Plots

Box-and-Whisker plots ou simplesmente box-plots são simples representações diagramáticas dos cinco números sumários: (mínimo, quartil inferior, mediana, quartil superior, máximo).
![boxplot](https://miro.medium.com/max/9000/1*2c21SkzJMf3frPXPAR_gZA.png)


### Variância de desvio padrão


a variância, uma medida de dispersão que mostra quão distantes os valores estão da média. Nesse caso, como estamos analisando todos os valores de cada funcionário, e não apenas uma “amostra”, trata-se do cálculo da variância populacional (var).

O cálculo da variância populacional é obtido através da soma dos quadrados da diferença entre cada valor e a média aritmética, dividida pela quantidade de elementos observados. Observe o cálculo simplificado para esse exemplo:

![var](https://static.mundoeducacao.uol.com.br/mundoeducacao/conteudo/calculo-variancia.jpg)

O desvio padrão (dp) é simplesmente o resultado positivo da raiz quadrada da variância.