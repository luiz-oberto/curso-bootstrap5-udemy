# Estruturando a galeria
Vamos agora estruturar através do HTML a nossa galeria de artes.
- Adicionando o seguinte código:
~~~html
<!-- index.html -->
 <!-- ... -->
<!-- GALLERY -->
       <div class="container" id="gallery-container">
        <div class="col-12">
            <h1>Artes em destaque</h1>
        </div>
        <div class="row gx-5"> <!--GUTTER-->
            <div class="col-12 col-md-6">
                <div class="small-image-container center-image" id="img2"></div>
                <h3>Obra de arthur</h3>
                <p class="secondary-color">Realizada em: 26/01/2018</p>
                <a href="#" class="btn">Detalhes</a>
            </div>
            <div class="col-12 col-md-6">
                <div class="small-image-container center-image" id="img3"></div>
                <h3>Grafite da Av. Paulista</h3>
                <p class="secondary-color">Realizada em: 14/06/2021</p>
                <a href="#" class="btn">Detalhes</a>
            </div>
            <div class="col-12 col-md-6">
                <div class="small-image-container center-image" id="img4"></div>
                <h3>Arte em conjunto do Metrô</h3>
                <p class="secondary-color">Realizada em: 19/01/2018</p>
                <a href="#" class="btn">Detalhes</a>
            </div>
            <div class="col-12 col-md-6">
                <div class="small-image-container center-image" id="img5"></div>
                <h3>Obra de Paulo</h3>
                <p class="secondary-color">Realizada em: 12/12/2015</p>
                <a href="#" class="btn">Detalhes</a>
            </div>
            <div class="col-12 col-md-6">
                <div class="small-image-container center-image" id="img6"></div>
                <h3>Grafite no centro da cidade</h3>
                <p class="secondary-color">Realizada em: 13/02/2012</p>
                <a href="#" class="btn">Detalhes</a>
            </div>
        </div>
       </div>
<!-- ... -->

~~~