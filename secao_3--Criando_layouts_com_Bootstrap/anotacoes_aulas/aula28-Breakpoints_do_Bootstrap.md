# Os Breakpoints do Bootstrap
- Os Breakpoints do Bootstrap são utilizados por classes como: *sm, md, lg*; -> dependendo de qual prefixo desses estiver presente, a aplicação vai funcionar de uma maneira diferente.
- Cada um representa uma *media query*;
- Então normalemte *adequamos outrso elementos* do nosso site a estes breakpoints;
- Assim é possível *Trabalhar com Conjunto do Bootstrap* e deixar o site responsivo;
- Vamos ver na prática!

1. Vamos começar acessando novamente a documentação do bootstrap, mais especificamente os Breakpoints dentro da seção de Layouts;
temos as seguintes relações:
~~~
Breakpoint       |   Class infix    | Dimensions
Extra small      | 	    None 	    |   <576px
Small            | 	     sm 	    |   ≥576px
Medium 	         |       md         |   ≥768px
Large 	         |       lg 	    |   ≥992px
Extra large      | 	     xl 	    |   ≥1200px
Extra extra large| 	     xxl        |   ≥1400px
~~~

2. com base nisso podemos começar a alterar nosso arquivo CSS adicionando media querys que mudará a cor do Título do nosso site de acordo com o tamanho da resolução da tela que estivermos trabalhando.
~~~css
/* XS -> extra small */
h1 {
    color: red;
}

/* SM >= 576px*/
@media (min-width: 576px) {
    h1 {
        color: blue;
    }
}

/* MD >= 768px */
@media (min-width: 768px) {
    h1 {
        color: green;
    }
}

/* LG >= 992px */
@media (min-width: 992px) {
    h1 {
        color: purple;
    }
}

/* XL >= 1200px */
@media (min-width: 1200px) {
    h1 {
        color: yellow;
    }
}

/* XXL >= 1400px */
@media (min-width: 1400px) {
    h1 {
        color: teal;
    }
}

.btn-primary {
    background-color: red;
}
~~~