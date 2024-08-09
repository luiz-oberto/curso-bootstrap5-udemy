# Alinhamento Horizontal
- O **alinhamento horizontal** segue a mesma premissa do vertical;
- **Utilizamos classes no elemento pai (row)** para condicionar os itens na linha horizontal;
- Para centralizar elementos podemos por a classe: **justify-content-center**;
- As regras  **end e start** também fucionam;
- Podemos **combinar** também vertical e horizontal;

No código:
~~~html
      <!-- Alinhamento Horizontal -->
      <div class="container vertical">
        <div class="row align-items-center justify-content-center">
            <div class="col-3"></div>
        </div>
      </div>

      <div class="container vertical">
        <div class="row justify-content-end">
            <div class="col-3"></div>
            <div class="col-3"></div>
        </div>
      </div>
~~~