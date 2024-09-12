# Estruturando os mini banners

~~~html
    <!-- BANNERS -->
    <div class="container" id="banners-container">
        <div class="carousel slide" id="slider" data-bs-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="img/banner1.jpg" alt="Banner 1" class="d-block w-100 img-fluid">
                    <div class="carousel-caption primary-bg-color">
                        <h5>Relógios de Luxo</h5>
                        <p>Para você estar pronto em qualquer situação</p>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="img/banner3.jpg" alt="Banner 3" class="d-block w-100 img-fluid">
                    <div class="carousel-caption primary-bg-color">
                        <h5>Linha Importada</h5>
                        <p>Conheça os melhores relógios suiços, com pronta entrega.</p>
                    </div>
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#slider" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#slider" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
        <div class="container" id="mini-banners">
            <div class="row justify-content-around">
                <div class="col-12 dark-bg-color" id="mini-banner-1">
                    <h2>Nova coleção</h2>
                    <img src="img/relogio1.png" alt="Relógio 1">
                    <a href="#">Compre agora</a>
                </div>
                <div class="col-12 secondary-bg-color" id="mini-banner-2">
                    <h2>Promoções</h2>
                    <img src="img/relogio2.png" alt="Relógio 2">
                    <a href="#">Compre agora</a>
                </div>
                <div class="col-12 light-bg-color" id="mini-banner-3">
                    <h2 class="secondary-color">Edição Limitada</h2>
                    <img src="img/relogio3.png" alt="Relógio 3">
                    <a href="#">Compre agora</a>
                </div>
            </div>
        </div>
    </div>
~~~