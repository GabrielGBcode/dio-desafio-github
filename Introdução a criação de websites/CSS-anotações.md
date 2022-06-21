# CSS3

Cascading Style Sheet (CSS), foi desenvolvido em 1996 devido a necessidade de formatar páginas após a criação do HTML, assim foi criada a linguagem de estilo conhecida como CSS.

A sintaxe é bem simples e pode ser explicada com a frase "você cria regras de estilo para elementos ou grupos de elementos".

Pode-se colocar vários elementos com uma mesma alteração sem necessitar de ficar copiando e colando o mesmo código, você pode apenas separa-las por vírgulas, por exemplo:

```css
h1, h2, h3 {
    color: #00ffff; /* Neste caso, o h1, o h2 e o h3 terão suas cores alteradas para ciano. */
}
```

### ID x Classe

Como no exemplo anterior, modificamos a cor para ciano, mas isso mudará a cor de todos os títulos h1, h2 e h3 que tiverem na página, e normalmente temos sites mais complexos que precisam de várias regras diferentes para elementos iguais.

Para que possamos modificar diferentes elementos iguais (como `p`), utilizaremos IDs e/ou Classes, com eles poderemos representar  qualquer tipo de elemento mas há algumas diferenças entre eles:

ID: é representado pelo simbolo `#` (hash) seguido do nome atribuido.

Classe: é representado pelo simbolo `.` (ponto) seguido do nome atribuido.

A difrença mais importante entre eles é a forma como devem ser usados: o ID só pode ser usado uma vem em uma página HTML, enquanto a classe não tem restrições.

#### Estrutura Básica

```css
body { /* Elemento que será alterado e Abertura de bloco*/
    background: #36393f; /* Alteração cor da página em hexadecimal*/
} /* Fechamento de bLoco*/

a:hover { /* Elemento que será alterado e Abertura de bloco*/
    color: #ff0000;
} /* Fechamento de bLoco*/

.photo { /* Elemento que será alterado e Abertura de bloco*/
    border: 2px solid #202020; /* Alteração da borda, adicionando um contorno sólido, cinza e com 2px de largura */
    border-radius: 50%; /* Alteração do raio da borda, tornando-a redonda */
} /* Fechamento de bLoco*/

#titulo { /* Elemento que será alterado e Abertura de bloco*/
    color: #8f46fe; /* Alteração da cor do título para roxo. */
} /* Fechamento de bLoco*/
```

#### Códigos na Prática

#### Box-model

```css
img {
    margin: 10px; /* Margem é o espaçamento entre elementos */
    border: 15px; /* Borda */
    padding: 20px; /* Padding é um espaçamento entre as bordas e o conteúdo. */
}
/* 
ABAIXO DEIXAREI UMA IMAGEM ILUSTRATIVA QUE REPRESENTE CADA UM DELES.
*/
```

![](C:\Users\Honter\Desktop\Visualizacao.png)

Nesta imagem, cada elemento possui um tamanho:

- Conteúdo: 20rem;

- Padding: 30px;

- border: 25px;

- margin: 30px;

##### Padding e Margin

Tem diversas maneiras de especificar o tamanho de um *`padding`* ou de uma *`margin`*, a seguir está descrito algumas formas:

```css
/* Apenas um valor para os 4 lados. */
border: 10px;
padding: 10px;

/* Dois valores distintos para o eixo X e o eixo Y */
/* Sendo 10px ao eixo Y (cima, baixo) e 20px ao eixo X (direita, esquerda). */
border: 10px 20px; 
padding: 10px 20px;


/* Quatro valores distintos para cada um dos lados. */
/* Sendo 10px para o topo, 15px para a direita, 20px para baixo e 25px para a esquerda. */
border: 10px 15px 20px 25px;
padding: 10px 15px 20px 25px;

/* Também é possível especificar um por um. */
margin-top: 10px;
margin-right: 15px;
margin-bottom: 20px;
margin-left: 25px;

padding-top: 10px;
padding-right: 15px;
padding-bottom: 20px;
padding-left: 25px;
```

##### Border

```css
/*
Existem algumas forma de representar as unidades, como:
    largura: px, em, mm, entre outros.
    cor: nome (em inglês), código hexadecimal, rgb, entre outros.
    Estilo: solid, dotted, dashed, entre outros.
*/

border: 20rem solid #00ff00;

/* Também é possível alterar cada propriedade por vez, por exemplo: */
border-width: 15px; /* Largura */
border-color: #0000ff; /* Cor */
border-style: dashed; /* Estilo */
```




