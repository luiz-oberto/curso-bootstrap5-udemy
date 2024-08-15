# Input Groups
- Os **inputs groups** serverm para darmos uma experiência melhor para o usuário;
- Às vezes **agrupando funções**;
- Ou tornando o input mais objetivo;

No código:
~~~html
            <!-- Input groups -->
             <div class="input-group mb-4">
                <span class="input-group-text" id="basic-addon">@</span>
                <input type="email" class="form-control" placeholder="Digite seu e-mail">
             </div>

             <div class="input-group mb-4">
                <span class="input-group-text">#</span>
                <input type="text" class="form-control" placeholder="Digite seu usuário">
             </div>

             <p>Quanto você quer depositar? (sem centavos)</p>
             <div class="input-group mb-4">
                <span class="input-group-text">R$</span>
                <input type="text" class="form-control" placeholder="Valor">
                <span class="input-group-text">,00</span>
             </div>
~~~