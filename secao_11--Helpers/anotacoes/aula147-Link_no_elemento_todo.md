# Link no elemento
- Este helper serve para **deixar o elemento todo clicável**;
- Ou seja, **podemos permitir o click em todo o card**, para levar a um link específico;
- **Sem esta classe envolvemos o elemento com uma tag a**, o que pode não ficar bom para a estética do código.;

~~~~html
    <!-- LINK ELEMENTO -->
     <div class="container m-4">
        <div class="card" style="width: 18rem;">
            <img src="https://via.placeholder.com/400" alt="imagem">
            <div class="card-body">
                <h5 class="card-title">Produto Legal</h5>
                <p class="card-text">Não o perca o calor promocional</p>
                <a href="https://google.com" class="btn btn-primary stretched-link">Comprar</a>
            </div>
        </div>
     </div>
~~~~