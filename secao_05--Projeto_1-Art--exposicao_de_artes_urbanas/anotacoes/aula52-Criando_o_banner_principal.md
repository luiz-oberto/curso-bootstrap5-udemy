# Criando o banner principal
Nesta aula vamos criar o banner principal do nosso site ajustando a imagem com algumas informações relevantes da imagem.

- Primeiro, os ajustes no index.html
~~~html
     <!-- MAIN IMAGE -->
      <div class="container" id="main-image-container">
        <div class="main-image center-image">
            <div class="main-image-info">
                <h2>Arte no muro de Davi</h2>
                <div class="secondary-color">Realizada em 20/05/2021</div>
                <a href="" class="btn">Detalhes</a>
            </div>
        </div>
      </div>
~~~

- Alterações feitas no style.css

~~~css
/* MAIN IMAGE */
.main-image {
    height: 400px;
    background-image: url('../img/g_1.jpg');
    margin-bottom: 30px;
    position: relative;
}

.main-image-info {
    background-color: #fff;
    padding: 25px;
    position: absolute;
    left: 25px;
    bottom: 25px;
}
~~~
Com isso temos nosso banner principal pronto