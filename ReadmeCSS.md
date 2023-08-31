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
    padding: 10px
}

#header {/*ID*/
    padiing: 15px
}
~~~
