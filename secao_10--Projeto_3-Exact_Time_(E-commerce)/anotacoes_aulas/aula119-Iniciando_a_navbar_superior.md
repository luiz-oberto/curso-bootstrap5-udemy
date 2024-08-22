# Iniciando a navbar superior
Nesta aula apenas estamos colocando os conteúdos da navbar sem a devida estilização. Aqui a única novidade que podemos mensionar é a *tag span* com a classe **qty-info** que vai indicar a quantidade de itens (ou notificaçõe) no em cimas dos icones de pessoa e bolsa.

No código:
~~~html
 <!-- NAVBAR -->
    <nav class="navbar navbar-expand-lg primary-bg-color py-4 px-2" id="navbar">
        <div class="container">
            <a href="#" class="navbar-brand">ExactTime</a>
            <div class="navbar-items">
                <div></div>
                <form action="d-flex" id="search-form">
                    <i class="bi bi-search primary-color"></i>
                    <input type="search" class="form-control me-2" placeholder="busque o seu relógio..." aria-label="Search">
                    <button class="btn secondary-bg-color" type="submit">Pesquisar</button>
                </form>
                <ul class="navbar-nav mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a href="#" class="nav-link">
                            <i class="bi bi-person"></i>
                        </a>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link">
                            <i class="bi bi-heart"></i>
                        </a>
                        <span class="qty-info">5</span>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link">
                            <i class="bi bi-bag"></i>
                            <b>R$90,12</b>
                        </a>
                        <span class="qty-info">8</span>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
~~~