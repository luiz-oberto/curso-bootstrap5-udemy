# Ratio
- Um Helper que serve para **manter a proporção de um elemento**;
- Podemos utilizar para **embed de vídeos**;
- Desta maneira o item não vai ficar desproporcional ao seu tamanho original;

~~~html
    <!-- RATIO -->
    <div class="container">
        <div class="col-md-4 mb-4">
            <div class="ratio ratio-16x9">
                <iframe src="https://www.youtube.com/watch?v=CPUKGFVrQvE" frameborder="0" allowfullscreen></iframe>
            </div>
        </div>
        <!-- imagem desfocada -->
        <div class="col-md-4 mb-4">
            <iframe src="https://www.youtube.com/watch?v=CPUKGFVrQvE" frameborder="0" allowfullscreen></iframe>
        </div>
    </div>
~~~