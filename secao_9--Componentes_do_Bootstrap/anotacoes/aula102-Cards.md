# Cards
- os **cards** são componentes bem interessantes;
- Podemos inserir **imagem, descrição um botão** de chamada;
- São utilizados para: Produtos, avatares e outros itens;
- Há **diversas variações** também;

No código:
~~~html
    <!-- Card -->
     <div class="container mb-4">
        <!-- card 1 -->
        <div class="card mb-4">
            <img 
            src="https://via.placeholder.com/300" 
            alt="Minha Imagem" 
            class="card-img-top">
            <div class="card-body">
                <p class="card-text">Esta é a descrição do produto.</p>
            </div>
        </div>


        <!-- card 2 -->
        <div class="card mb-4">
            <img 
            src="https://via.placeholder.com/300" 
            alt="Minha Imagem" 
            class="card-img-top">
            <div class="card-body">
                <h5 class="card-title">Título do card</h5>
                <p class="card-text">Esta é a descrição do produto.</p>
                <a href="#" class="btn btn-primary">Comprar</a>
            </div>
        </div>

        <!-- card 3 -->
        <div class="card mb-4">
            <div class="card-body">
                <h5 class="card-title">Título do card</h5>
                <h6 class="card-subtitle mb-2 text-muted">Um subtítulo</h6>
                <p class="card-text">Esta é a descrição do produto.</p>
                <a href="#" class="card-link">Comprar</a>
                <a href="#" class="card-link">cancelar</a>
            </div>
        </div>

        <!-- card banner -->
         <div class="card text-center" id="card-banner">
            <div class="card-header">
                Card banner
            </div>
            <div class="card-body">
                <h5 class="card-title">Um título legal</h5>
                <p class="card-text">Esta é uma descrição desse banner, é uma descrição maior do que os outros cards</p>
                <a href="#" class="btn btn-success">Acessar oferta</a>
            </div>
            <div class="card-footer text-muted">
                Faltam 2 dias
            </div>
         </div>

     </div>
~~~
