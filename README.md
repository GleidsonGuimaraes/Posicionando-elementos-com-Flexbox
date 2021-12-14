# Posicionando itens com Flexbox em CSS

![Gif P_E_FlexBox](projeto-integrador/images/P_E_FlexBox.gif)

## Display: flex;

* Indica que os elementos interno de um outro elemento, estão organizados dentro de um conteiner.

## Flex-direction: row, row-reverse, column, column-reverse;

* Indica como os elementos serão organizados dentro desse conteiner, podendo ser em linha ou coluna.

## Flex-wrap: nowrap, wrap, nowrap-reverse, wrap-reverse;

* Realiza a organização dos elementos dentro de um conteiner, não permitindo que sobrem elementos para fora deste.

## Flex-flow: flex-direction flex-wrap;

* O Flex-flow é uma abreviação para as duas propriedades anteriores. Ele recebe dois valores, sendo eles do flex-direction e flex-wrap, respectivamente.

## Justify-content: flex-start, flex-end, center, space-between, space-around;

* É responsável por alinhar os itens dentro do conteiner de acordo com a direção pretendida.
* * Flex-start: posiciona os itens no inicio do conteiner.
* * Flex-end: posiciona os itens no final do conteiner.
* * Center: posiciona os itens no meio do conteiner.
* * Space-between: define espaçamentos iguais ***entre*** os itens que estão dentro do conteiner.
* * Space-around: define o espaçamento de igual tamanho ***ao redor*** dos itens que estão dentro do conteiner.

## Align-items: flex-start, flex-end, center, baseline, stretch;

* É responsável pelo alinhamento dos itens seguindo o eixo do conteiner.
* * Flex-start, Flex-end e center, seguem com as mesmas definições aplicadas no Justify-content, porém, seguindo o eixo como referência.
* * Stretch: faz com que os itens preencham todo o espaço do conteiner.
* * Baseline: faz com que os itens se alinhem de acordo com a linha base de um texto.

## Align-content: center, stretch, flex-start, flex-end, space-between, space-around;

* É a propriedade responsável por tratar o alinhamento das linhas do conteiner em relação ao seu eixo vertical.

***

## Formatando itens do conteiner

***

## Flex-grow: 0, 1, 2, 3, ...;

* Este é responsável por definir o tamanho de um elemento em relação aos outros presentes dentro de um determinado conteiner.

## Flex-basis: auto, (x)px, (x)%, (x)em, ..., 0;

* O Flex-basis define o tamanho dos itens levando em consideração o conteúdo interno de cada um. Sendo assim, ele é responsável por definir o tamanho das partes sobresalentes de cada item em relação ao seu conteúdo interno.

## Flex-shrink: 0, 1, 2, 3, ...;

* Responsável por comprimir os itens contidos dentro do conteiner levando em consideração o conteúdo seu conteúdo interno. O flex-grow e o flex-basis podem influenciar essa formatação.

## Flex: grow, shrink e basis;

* É uma abreviação para as propriedades flex-grow, flex-shrink e flex-basis, respectivamente.

## Order: ;

* Responsável por organizar os elementos. Para que ele funcione, é necessário que tenha outro como parâmetro.

## Align-self: auto, flex-start, flex-end, center, stretch, baseline;

* É a propriedade que estabelece o alinhamento de modo individual sobre um determinado item.
* * A valor auto já vem setado por padrão.