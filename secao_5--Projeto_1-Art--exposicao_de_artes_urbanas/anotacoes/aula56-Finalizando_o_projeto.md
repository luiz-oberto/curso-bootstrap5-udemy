# Finalizando o projeto

Para finalizar este projeto vamos adicionar estilização ao footer do nosso projeto:

~~~css
/* FOOTER */

footer {
    border-top: 1px solid #ccc;
    height: 250px;
    padding: 30px;
}

footer i {
    font-size: 20px;
}

#social-icons-container {
    padding: 25px;
}

#social-icons-container div {
    text-align: center;
}

footer p {
    text-align: center;
    margin: 20px;
}

a:hover i {
    color: #C1B696;
}
~~~

vamos ajustar também nosso gutter no index.html:
~~~html
        <div class="row gx-md-5">
~~~
- Essa linha nos ajuda a ajustar um pequeno erro de alinhamento em que podemos encontrar quando utilizarmos dispositivos mobile

Com isso finalizamos nosso projeto deixando já responsivo para dispositivos mobile.