# NavBar
- A navbar é o componente para as **barras de navegação**;
- Temos diversas variações;
- Podemos colcoar **ícones, links, dropdowns e mais**;
- Nesta aula vamos continuar em outro arquivo html de mesmo nome mas num diretório chamado 2_aulas

No código:
~~~html
    <!-- NavBar 1 -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <a href="#" class="navbar-brand">Meu Projeto</a>
            <button 
            class="navbar-toggler" 
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle Navigation"
            >
                <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a href="#" class="nav-link active" aria-current="page">Home</a>
                </li>
                <li class="nav-item">
                    <a href="#" class="nav-link" aria-current="page">Produtos</a>
                </li>
                <li class="nav-item dropdown">
                    <a href="#" class="nav-link dropdown-toggle" id="navbarDropdown" role="button"
                    data-bs-toggle="dropdown"
                    aria-expanded="false"
                    >
                        Categorias
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                        <li><a href="#" class="dropdown-item">Cat A</a></li>
                        <li><a href="#" class="dropdown-item">Cat B</a></li>
                        <li><a href="#" class="dropdown-item">Cat C</a></li>
                    </ul>
                </li>
                <li class="nav-item">
                    <a href="#" class="nav-link" aria-current="page">Blog</a>
                </li>
                <li class="nav-item">
                    <a href="#" class="nav-link" aria-current="page">Contato</a>
                </li>

            </ul>
        </div>
        </div>
    </nav>

    <!-- Navbar 2 -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a href="#" class="navbar-brand">Meu Projeto</a>
            <button 
            class="navbar-toggler" 
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav2"
            aria-controls="navbarNav2"
            aria-expanded="false"
            aria-label="Toggle Navigation"
            >
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav2">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a href="#" class="nav-link active" aria-current="page">Link 1</a>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link">Link 2</a>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link">Link 3</a>
                    </li>
                </ul>
            </div>
            <form class="d-flex">
                <input type="search" class="form-control me-2" placeholder="Digite algo..." aria-label="Search">
                <button class="btn btn-outline-primary" type="submit">
                    Pesquisar
                </button>
            </form>
        </div>
    </nav>
~~~

<nav class="navbar navbar-expand-lg navbar-light bg-light"></nav>

### nav-bar-expand
- serve para se expandir quando a tela ficar grande

### navbar-light
- Deixa a navbar clara

###  bg-light
- cor de fundo