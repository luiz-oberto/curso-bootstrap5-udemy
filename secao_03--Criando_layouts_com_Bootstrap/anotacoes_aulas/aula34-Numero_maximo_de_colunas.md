# Limitando número de colunas
- Podemos também **limitar a quantidae de colunas** em uma row;
- A classe a ser utilizada é: **row-cols-***;
- Onde * é o número limite;
- Assim o **grid sempre vai respeitar este número** máximo na linha;

No código:
~~~html
<!-- limitação de colunas -->
     <div class="container">
        <div class="row row-cols-2">
            <div class="col"></div>
            <div class="col"></div>
        </div>
        <div class="row row-cols-2">
            <div class="col"></div>
            <div class="col"></div>
        </div>
        <div class="row row-cols-2">
            <div class="col"></div>
            <div class="col"></div>
        </div>
     </div>
~~~