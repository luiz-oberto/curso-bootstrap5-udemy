# Grid
- *Grid* é a estrutura para criar layouts com Bootstrap;
- Temos um *grid colunar*, dividido em *12 colunas*;
- A estrutura do grid é sempre: *container > row > colunas*;
- Onde temos o *container* para abrigar a seção;
- *Row* para determinar uma linha (largura 100%);
- *Colunas* para  subdividir  o container em até 12 partes;

Vamos para nosso index.html

~~~html
    <div class="container">
        <div class="row">
            <div class="col">
                <p>Produto A</p>
            </div>
            <div class="col">
                <p>Produto B</p>
            </div>
        </div>
        <div class="row">
            <div class="col">
                <p>Produto C</p>
            </div>
            <div class="col">
                <p>Produto D</p>
            </div>
            <div class="col">
                <p>Produto E</p>
            </div>
        </div>
    </div>
~~~