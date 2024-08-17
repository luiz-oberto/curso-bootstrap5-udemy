# Close button
- O close button é um **componente do botão fechar**;
- Porém **não precisamos dos ícones** instalados;
- O que torna uma **vantagem** neste sentido, caso queremos utilizar ourtos ícones

No código:
~~~html
    <!-- Close Button -->
    <div class="container mb-4"> <!-- mb -> margin bottom-->
        <p>
            Clique para fechar 
            <button class="btn-close" type="button" aria-label="Close"></button>
        </p>
        <a href="#" class="btn btn-danger">
            Fechar
            <button class="btn-close" type="button" aria-label="Close"></button>
        </a>

        <!-- Desabilitada -->
        <p>
            Clique para fechar 
            <button class="btn-close" type="button" aria-label="Close" disabled></button>
        </p>
    </div>
~~~