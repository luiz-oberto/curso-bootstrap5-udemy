# Slider
- Podemos criar também um **slider** com Bootstrap;
- O nome do componente é **carousel**
- Há recursos para **passar a imagem** e também para **exibir a quantidade delas**

No código
~~~html
    <!-- SLIDER -->
    <div class="container mb-4">
        <div class="col-8">
            <div id="carousel" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-indicators">
                    <button 
                        class="active" 
                        type="button" 
                        data-bs-target="#carousel" 
                        data-bs-slide-to="0"
                        aria-current="true"
                        aria-label="slide 1"
                    ></button>
                    <button 
                        class="active" 
                        type="button" 
                        data-bs-target="#carousel" 
                        data-bs-slide-to="1"
                        aria-current="true"
                        aria-label="slide 2"
                    ></button>
                    <button 
                        class="active" 
                        type="button" 
                        data-bs-target="#carousel" 
                        data-bs-slide-to="2"
                        aria-current="true"
                        aria-label="slide 3"
                    ></button>
                </div>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img 
                        src="http://via.placeholder.com/600" 
                        alt="Descrição 1" 
                        class="d-block w-100">
                    </div>
                    <div class="carousel-item">
                        <img 
                        src="http://via.placeholder.com/600" 
                        alt="Descrição 2" 
                        class="d-block w-100">
                    </div>
                    <div class="carousel-item">
                        <img 
                        src="http://via.placeholder.com/600" 
                        alt="Descrição 3" 
                        class="d-block w-100">
                    </div>
                </div>
                <button 
                    class="carousel-control-prev" 
                    type="button" 
                    data-bs-target="#carousel"
                    data-bs-slide="prev">

                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                    </button>

                <button 
                    class="carousel-control-next" 
                    type="button" 
                    data-bs-target="#carousel"
                    data-bs-slide="next"
                    >

                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
            </div>

        </div>
    </div>

    <!-- SLIDER -->
    <div class="container mb-4">
        <div class="col-8">
            <div id="carousel2" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-indicators">
                    <button 
                        class="active" 
                        type="button" 
                        data-bs-target="#carousel2" 
                        data-bs-slide-to="0"
                        aria-current="true"
                        aria-label="slide 1"
                    ></button>
                    <button 
                        class="active" 
                        type="button" 
                        data-bs-target="#carousel2" 
                        data-bs-slide-to="1"
                        aria-current="true"
                        aria-label="slide 2"
                    ></button>
                    <button 
                        class="active" 
                        type="button" 
                        data-bs-target="#carousel2" 
                        data-bs-slide-to="2"
                        aria-current="true"
                        aria-label="slide 3"
                    ></button>
                </div>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img 
                        src="http://via.placeholder.com/600" 
                        alt="Descrição 1" 
                        class="d-block w-100">
                        <div class="carousel-caption">
                            <h5>Primeiro slide</h5>
                            <p>alguma decrição</p>
                        </div>
                    </div>
                    <div class="carousel-item">
                        <img 
                        src="http://via.placeholder.com/600" 
                        alt="Descrição 2" 
                        class="d-block w-100">
                        <div class="carousel-caption">
                            <h5>Segudo slide</h5>
                            <p>alguma decrição</p>
                        </div>
                    </div>

                    <div class="carousel-item">
                        <img 
                        src="http://via.placeholder.com/600" 
                        alt="Descrição 3" 
                        class="d-block w-100">
                        <div class="carousel-caption">
                            <h5>Terceiro slide</h5>
                            <p>alguma decrição</p>
                        </div>
                    </div>
                </div>
                <button 
                    class="carousel-control-prev" 
                    type="button" 
                    data-bs-target="#carousel2"
                    data-bs-slide="prev">

                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                    </button>

                <button 
                    class="carousel-control-next" 
                    type="button" 
                    data-bs-target="#carousel2"
                    data-bs-slide="next"
                    >

                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
            </div>

        </div>
    </div>

~~~