# Alinhamento vertical
- As colunas dentro de uma row **estão condicionadas ao flex box**;
- Ou seja, temos **classes bem parecidascom as regras de flex** para alinhá-las;
- Exemplo: **align-items-end** alinha no fim da row;
- Lembrando que esta classe **sempre deve ficar no elemento pai** (row)

NO código:
~~~html
     <!-- Alinhamento vertical -->
      <div class="container vertical">
        <div class="row align-items-end">
            <div class="col-6"></div>
            <div class="col-6"></div>
        </div>
      </div>

      <div class="container vertical">
        <div class="row align-items-center">
            <div class="col-6"></div>
            <div class="col-6"></div>
        </div>
      </div>
~~~