# Tamanho das colunas
- Podemos *ajustar o tamanho das colunas*;
- Para ocupar três espaços: *cols-3*;
- Lembrando que podemos separar em no máximo **12 divisões**
- E o espaço ocupado será  porporcional, ou seja, em col-11 e col-1, teremos uma coluna ocupando quase 100% da largura da row;

Na prática:

~~~html
<!-- Tamanho das coluna -->
    <div class="container">
        <div class="row">
            <div class="col-4"></div>
            <div class="col-2"></div>
        </div>

        <div class="row">
            <div class="col-1"></div>
            <div class="col-11"></div>
        </div>

        <div class="row">
            <div class="col-4"></div>
            <div class="col-4"></div>
            <div class="col-4"></div>
        </div>
     </div>

    <div class="container" id="largura-limitada">
        <div class="row">
            <div class="col-4"></div>
            <div class="col-4"></div>
            <div class="col-4"></div>
        </div>
    </div>
~~~