# Range
- **Range** é um input interessante;
- Onde o usuário pode **regular por uma barra**;
- E ainda podemos definir um **valor mínimo e máximo**;
- Temos componentes no Bootstrap para isso também;

No código:
~~~html
            <!-- Range -->
             <div class="mb-4">
                <h2>Por favor responda:</h2>
                <label for="probabilidade" class="form-label">Qual a probabilidade de indicar este site para laguém?</label>
                <input type="range" class="form-range" min="0" max="5" id="probabilidade">
             </div>
             <!-- disable -->
             <div class="mb-4">
                <h2>Por favor responda:</h2>
                <label for="probabilidade" class="form-label">Qual a probabilidade de indicar este site para laguém?</label>
                <input type="range" class="form-range" min="0" max="5" id="probabilidade" disabled>
             </div>
~~~