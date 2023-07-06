# PRÉ DIMENSIONAMENTO LAJE

## Altura da laje

  A espessura da laje leva em conta as suas dimensões no seu plano e as especificações das normas técnicas. Portanto, a primeira etapa consiste em determinar os vãos teóricos (ℓ) das lajes nas duas direções (x, y):

   * ℓx, correspondendo à borda menor da laje; e
   * ℓy, correspondendo à borda maior da laje.

<div align="center">

![Medidas da laje](https://static.wixstatic.com/media/e1eced_ac5ef2fd2b5a47d786cdee5d03372d11~mv2.png/v1/fill/w_600,h_274,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/e1eced_ac5ef2fd2b5a47d786cdee5d03372d11~mv2.png)

</div>

## Espessuras mínimas (h_min)

As espessuras das lajes devem respeitar os seguintes limites mínimos, conforme a NBR 6118 (2014):

* 7 cm para lajes de cobertura não em balanço; 
* 8 cm para lajes de piso não em balanço;
* 10 cm para lajes em balanço (de cobertura ou de piso);
* 12 cm para lajes que estejam sujeitas à trânsito de veículos, com até três toneladas;
* 15 cm par lajes que estejam sujeitas à trânsito de veículos, com mais de três toneladas.

  No caso, onde irá fazer o dimensionamento de um ponto de ônibus com três pilares, têm-se uma cobertura em balanço, dessa forma a altura mínima da laje é 10 cm.

  ## Cálculos

  Dados:
  * lx = 150 cm
  * ly = 450 cm
 
    Contudo, antes de aplicar o conceito de pré-dimensionamento é necessário classificar as lajes como armadas em uma direção ou duas direções. Essa classificação pode
ser feita pela consideração do fator λ = ly⁄lx, sendo essa uma classificação geométrica do elemento em função da disposição da armadura na peça. Tais
situações são descritas a seguir:

* a) λ > 2: Laje armada em uma direção: As barras para suprimir os esforços de tração são dispostas sempre em lx e barras construtivas são dispostas em ly.
* b) λ ≤ 2: Laje armada em duas direções: As barras para suprimir os esforços de tração são dispostas sempre nas duas direções em planta lx e ly.

No caso, λ = 3, sendo então uma laje armada em uma direção.

Dessa forma, a partir desse resultado, para lajes maciças em concreto armado, Rebello (2007), estabelece os seguintes critérios:

a) Laje armada em duas direções:

$$
h = 2% . \frac{lx + ly}{2}
$$

b) Laje armada em uma direção:

$$
h = 2% . lx
$$

c) Lajes em balanço:

$$
h = 4% . lx
$$
