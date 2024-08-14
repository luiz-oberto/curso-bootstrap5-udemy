# Form control
- **form-control** é uma classe para ajustar os inputs;
- Fazendo com que eles fiquem no padrão do bootstrap;
- Ou seja, **na maioria dos inputs adicioanamos esta classe**;
- Temos variações com: **form-control***;
- Onde * pode ser sm, lg (**variações de tamanho**);
- E a label leva a classe **form-label**;

o código:
~~~html
  <!-- Form control -->
     <div class="m-4">
        <form>
            <div class="col-4 mb-4">
                <label for="title" class="form-label">Título de Post:</label>
                <input type="text" class="form-control form-control-lg" id="title" placeholder="Digite seu título">
            </div>
            <div class="col-4 mb-4">
                <label for="content" class="form-label">Conteúdo:</label>
                <textarea class="form-control" rows="5" placeholder="Digite o conteúdo do Post..."></textarea>
            </div>
            <button type="submit" class="btn btn-success">Enviar</button>
        </form>
     </div>

     <div class="m-4">
        <form>
            <div class="col-4 mb-4">
                <label for="title" class="form-label">Título de Post:</label>
                <input type="text" class="form-control form-control-sm" id="title2" placeholder="Digite seu título">
            </div>
            <div class="col-4 mb-4">
                <label for="content" class="form-label">Conteúdo:</label>
                <textarea class="form-control" rows="5" placeholder="Digite o conteúdo do Post..."></textarea>
            </div>
            <button type="submit" class="btn btn-success">Enviar</button>
        </form>
     </div>
~~~