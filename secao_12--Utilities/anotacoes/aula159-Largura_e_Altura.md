# Largura e Altura
- Há classes que nos permitem alterar os atributos de **altura e largura** de um elemento;
- **Podemos então criar "colunas"** com diferentes opções além do grid de 12;

~~~html
        <!-- LARGURA E ALTURA -->
         <!-- largura de 25%, 50%, 75% e 100% -->
        <div class="w-25 bg-primary">a</div>
        <div class="w-50 bg-info">b</div>
        <div class="w-75 bg-success">c</div>
        <div class="w-100 bg-info">d</div>

        <div class="container altura m-4">
            <div class="row h-100">
                <div class="col-3 h-25 bg-primary">a</div>
                <div class="col-3 h-50 bg-info">b</div>
                <div class="col-3 h-75 bg-primary">c</div>
                <div class="col-3 h-100 bg-info">d</div>
            </div>
        </div>
~~~