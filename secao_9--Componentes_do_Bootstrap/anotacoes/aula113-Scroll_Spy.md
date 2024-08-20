# SrollSpy
- O **Scrollspy** é um componente para levar a barra de navegação a um local indicado;
- Geralmente utilizado para **fixar as seções do site**;
- Ao clicar em um botão **o scroll desce**;

No código:
~~~html
    <!-- Scroll Spy -->
     <nav id="scrollspy" class="navbar navbar-light bg-light px-3 mb-4">
        <a href="#" class="navbar-brand">Minha marca</a>
        <ul class="nav">
            <li class="nav-item">
                <a href="#secao-1" class="nav-link">Secao 1</a>
            </li>
            <li class="nav-item">
                <a href="#secao-2" class="nav-link">Secao 2</a>
            </li>
        </ul>
     </nav>

     <div 
        data-bs-spy="scroll" 
        data-bs-target="#scrollspy" 
        data-bs-offset="0" 
        tabindex="0">
            <h4 id="secao-1">Secao 1</h4>
            <p class="mb-4">Conteúdo</p>
            <p class="mb-4">Conteúdo</p>
            <p class="mb-4">Conteúdo</p>
            <p class="mb-4">Conteúdo</p>
            <p class="mb-4">Conteúdo</p>
            <p class="mb-4">Conteúdo</p>
            <p class="mb-4">Conteúdo</p>
            <p class="mb-4">Conteúdo</p>
            <p class="mb-4">Conteúdo</p>
            <p class="mb-4">Conteúdo</p>
            <p class="mb-4">Conteúdo</p>
            <p class="mb-4">Conteúdo</p>
            <p class="mb-4">Conteúdo</p>
            <p class="mb-4">Conteúdo</p>
            <p class="mb-4">Conteúdo</p>
            <h4 id="secao-2">Secao 2</h4>
            <p class="mb-4">Conteúdo da secao 2</p>
            <p class="mb-4">Conteúdo da secao 2</p>
            <p class="mb-4">Conteúdo da secao 2</p>
            <p class="mb-4">Conteúdo da secao 2</p>
            <p class="mb-4">Conteúdo da secao 2</p>
            <p class="mb-4">Conteúdo da secao 2</p>
            <p class="mb-4">Conteúdo da secao 2</p>
            <p class="mb-4">Conteúdo da secao 2</p>
            <p class="mb-4">Conteúdo da secao 2</p>
            <p class="mb-4">Conteúdo da secao 2</p>
            <p class="mb-4">Conteúdo da secao 2</p>
    </div>
~~~

### px-3
- padding no eixo "x" de 3