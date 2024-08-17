# Collapse
- **Collapse** é um componente que tem duas partes;
- **Um texto**, que será exibido condicionado a um evento de click em um botão;
- **Um botão**, que exibe ou esconde o texto;
- a idéia é para textos únicos;;

No código:
~~~html
    <!-- Collapse -->
    <div class="container mb-4">
        <button class="btn btn-primary" type="button" data-bs-toggle="collapse" data-bs-target="#collapse" aria-expanded="false" aria-controls="collapse">
            Clique para exibir/esconder
        </button>
        <div class="collapse" id="collapse">
            <div class="col-12 mt-4">
                Este é texto que pode ser exibido ou não dependendo do clique ou não.
            </div>
        </div>
    </div>
~~~