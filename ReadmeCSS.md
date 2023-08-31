# CSS
## ID x Class
ID's e Class servem para diferenciar elementos de mesma tag mas que tem estilos diferentes na nossa página ex.: um cabeçalho da pagina e um cabeçalho de um artigo, ambos são cabeçalhos mas eles têm estilos diferentes e então utilizamos class e ID's para diferencia-los. 
Note que o ID só pode ser utilizado uma vez por página. 
#### No html eles são declarados assim:
~~~
<header id-"header" class="header">Cabeçalho</header>
<header class="header">Cabeçalho</header>
~~~
#### No css eles são chamados assim:
~~~
.header {/*classe*/
    padding: 10px;

}

#header {/*ID*/
    padiing: 15px
}
~~~
## Elementos css
boxmodel -> forma de divisão do css (caixas dentro de caixas)  
margin -> espaçamento entre elementos  
padding -> espaçamento entre o bloco e seu conteúdo
~~~
padding: 10px 5px; /*x, y do plano cartesiano*/
    padding: 15px 10px 5px 0; /*Top Right Bottom Left*/
    padding-top(-etc)
~~~ 
background -> fundo (com ele podemos alterar a cor do fundo)  
~~~
background-color: green;
background-image: url(caminho.png);
background-position: top;
~~~
border -> borda da boxModel, ela tem três elementos, tamanho, estilo e cor. border-radius para arredondar   
~~~
border: 3px solid blue
border-radius: 10px
~~~
font-family -> altera a fonte  
font-size -> tamanho da fonte  
font-style -> (negrito, itálico)  
font-weight-> (peso da fonte)  
text-transform -> (lower ou uppercase)  
text-decoration-> (overline, underline)  