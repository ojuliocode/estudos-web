## Propriedade Flex
Este pequeno artigo tem como objetivo explicar a propriedade flex, e quais outras propriedades estão embutidas nela:

Quando colocamos ```flex: 1``` em alguma classe, estamos especificando, na verdade, três outras propriedades:

```
flex-grow
flex-shrink
flex-basis
```

As palavras <b> grow e shrink </b> têm os significados, respectivamente, de "crescer" e "diminuir". Ou seja, essas duas propriedades têm relação com o crescimento ou decrescimento do filho 

A declaração ```flex: 1 ``` é equivalente às seguintes propriedades

```
div {
    flex-grow: 1;
    flex-shrink: 1;
    flex-basis: 0;
} 
```

A propriedade flex-grow indica o fator de crescimento de um filho. Se, por exemplo, colocássemos o flex-grow e apenas um filho como sendo 2, automaticamente ele iria crescer 2x mais do que os outros filhos

De maneira semelhante, se tivéssemos divs filhos com largura de 250px, e setássemos o flex-shrink de apenas uma div para 0, ele nunca iria diminuir para menos que 250px