# Estruturando o Header
O header é o cabeçalho da nossa aplicação dentro da tag *body*. Nele vamos encontrar coisas como:
- Título do site
- subtítulo
- Imagem de logo do site
- Links de navegação do site
- etc.

no HTML ele fica assim:
~~~html
<body>
    <!-- HEADER -->
     <div class="container-fluid">
        <header class="row" id="header">
            <div id="logo-container">
                <img src="img/art_logo.svg" alt="Art" id="logo">
                <h1>Art</h1>
            </div>
            <p>Exibições de arte urbana</p>
        </header>
        <nav id="navbar" class="container">
            <div class="row justify-content center">
                <a href="#">Home</a>
                <a href="#">Projetos</a>
                <a href="#">Artistas</a>
                <a href="#">Contato</a>
            </div>
        </nav>
     </div>
     <!-- ... -->
</body>
~~~

No CSS, podemos adiantar alguns elementos que vamos colocar futuramente:
~~~css
/* Estilos gerais */
* {
    color: #25282E;
}

a, i {
    transition: .5s;
    text-decoration: none;
}

.secondary-color {
    color: #555;
}

.center-image {
    /* isso vai ajudar a gente a centralizar a imagem e fazer com que ela se adapte ao máximo possível ao tamanho da div */
    background-size: cover;
    background-position: center;
}

.btn {
    text-decoration: none;
    background-color: #25282E;
    color: #FFF;
    padding: 7px 18px;
    border-radius: 0;
}

.btn:hover {
    background-color: #333;
    color: #FFF;
}
~~~