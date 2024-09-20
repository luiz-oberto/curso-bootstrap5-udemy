# Espaçamentos
- Podemos **alterar o espaçamento** dos elementos ia classes;
- Ou seja, é possível alterar o **padding e margin**;
- Podemos também escolher a direção que será colocado espaçamento: **top, right, bottom ou left**;

- Obs: alguma notações para tomar
    - p -> padding
    - m -> margin
    - pt -> padding top
    - mt -> margin top
    - ps -> padding a esquerda
    - pb -> paddint-bottom
    - ms -> margin a esquerda
    - mb -> margin-bottom

~~~html
        <!-- ESPAÇAMENTOS -->
        <div class="p-0 m-0 box">0</div>
        <div class="p-2 m-2 box">2</div>
        <div class="p-4 m-4 box">4</div>

        <div class="pt-5 mt-5 box">top 5</div>
        <div class="ps-2 pb-4 ms-2 mb-4 box">left 2 bottom 4</div>
~~~

~~~css
.box {
    border: 1px solid red;
}
~~~