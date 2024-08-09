# Ordem dos elementos
- É possível **alterar a ordem qe os itens são exibidos**;
- Vamos colocar a classe: **order-***;
- Onde * é a posição do elemento, sendo **1 o primeiro**;
- Este recurso é útil no **desenvolvimento mobile**, onde os elementos costumam mudar de ordem;

No código:
~~~html
    <div class="container vertical">
        <div class="row">
            <div class="col-sm-12 col-3 order-3">3</div>
            <div class="col-sm-12 col-3 order-1">1</div>
            <div class="col-sm-12 col-3 order-4">4</div>
            <div class="col-sm-12 col-3 order-2">2</div>
        </div>
    </div>
~~~