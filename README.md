Confesso que esse projeto foi um desafio, no começo tentei pensar sobre como eu poderia posicionar os itens de maneira mais simples possivel (já que meu objetivo é sempre fazer codigos simples e fáceis de manutenção), e falhei miseravelmente. 

I confess that this project was a little difficult, at first I tried to think about how I could position the items in the simplest possible way (since my goal is always to make simple and maintainable codes), and I failed miserably.

At first I tried to make a grid in the Body with two columns at the top to put the Text and the ratings and three columns at the bottom for the cards, it didn't end up working as I planned (at least I realized that I needed to train more flexbox and grid XD).

In short, the solution I found was to make three elements: the texts, the ratings and the cards,

I did the positioning of the text and the evaluations using grid, I positioned the evaluations diagonally with a "subgrid" and in it I used properties grid-template-columns and grid-template-rows according to the position of the elements, grid-column-start grid -column-end to position them within these grids I did the same with the cards.



No começo tentei fazer um grid no body com duas colunas em cima para colocar o titulo e as avaliações e tres colunas em baixo para os cards, não acabou funcionando como eu planejava (pelo menos eu percebi que precisava treinar mais flexbox e grid XD).

Resumindo, a solução que encotrei foi fazer três elementos: os textos, as avaliações e os cards, 

Fiz o posicionamento do texto e as avaliações usando grid, posicionei as avaliaçoes na diagonal com uma "subgrid" e nela usei propriedades grid-template-columns e grid-template-rows de acordo com a posição dos elementos, grid-column-start grid-column-end para posicionar eles dentro dessas grids fiz o mesmo com os cards.
