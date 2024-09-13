# Button Group
- O Button Group é um **agrupamento de botões**;
- Onde podemos criar componentes como **paginação**;
- Ou se precisarmos, **botão unidos** que configuram algo

No código:
~~~html
   <!-- button group -->
     <div class="container mb-4">
        <h2>Configure a seção:</h2>
        <div class="btn-group" role="group" aria-label="Exemplo">
            <button class="btn btn-success" type="button">Diminuir</button>
            <button class="btn btn-success" type="button">Confirmar</button>
            <button class="btn btn-success" type="button">Aumentar</button>
        </div>

        <div class="btn-group" role="group" aria-label="Exemplo 2">
            <button class="btn btn-outline-secondary" type="button">1</button>
            <button class="btn btn-outline-secondary" type="button">2</button>
            <button class="btn btn-outline-secondary" type="button">3</button>
            <button class="btn btn-outline-secondary" type="button">4</button>
        </div>

        <h2>Vertical</h2>
        <div class="btn-group-vertical" role="group" aria-label="Exemplo 3">
            <button class="btn btn-warning" role="button">Opção 1</button>
            <button class="btn btn-warning" role="button">Opção 2</button>
            <button class="btn btn-warning" role="button">Opção 3</button>
        </div>
     </div>
~~~