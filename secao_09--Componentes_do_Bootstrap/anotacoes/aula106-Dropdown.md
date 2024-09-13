# Dropdown
- O dropdown é um **componente para menu**;
- Onde podemos colocar **um botão, com moum evento**;
- Ao clicar nele, **abrimos uma lista** com os demais itens do menu;

No código:
~~~html
    <!-- Dropdown -->
    <div class="container mb-4">
        <div class="dropdown mb-4">
            <a href="#" class="btn btn-secondary dropdown-toggle" role="button" id="dropdown" 
            data-bs-toggle="dropdown" aria-expanded="false">Clique aqui</a>

            <ul class="dropdown-menu" aria-labelledby="dropdown">
                <li><a href="#" class="dropdown-item">Link 1</a></li>
                <li><a href="#" class="dropdown-item">Link 2</a></li>
                <li><a href="#" class="dropdown-item">Link 3</a></li>
                <li><a href="#" class="dropdown-item">Link 4</a></li>
            </ul>
        </div>

        <!-- A DIREITA -->
        <div class="dropdown mb-4 dropend">
            <a href="#" class="btn btn-secondary dropdown-toggle" role="button" id="dropdown-direita" 
            data-bs-toggle="dropdown" aria-expanded="false">Clique aqui</a>

            <ul class="dropdown-menu" aria-labelledby="dropdown-direita">
                <li><a href="#" class="dropdown-item">Link 1</a></li>
                <li><a href="#" class="dropdown-item">Link 2</a></li>
                <li><a href="#" class="dropdown-item">Link 3</a></li>
                <li><a href="#" class="dropdown-item">Link 4</a></li>
            </ul>
        </div>
    </div>    
~~~