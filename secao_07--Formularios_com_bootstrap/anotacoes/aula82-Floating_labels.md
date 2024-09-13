# Label Flutuante
- As **Floating Labels** são uma forma de deixar a label dentro do input;
- Semelhante aos **formulários do Google**;
- **Ocupando menos espaços** e deixando o layout bonito;

No código:
~~~html
             <!-- FLoating labels -->
             <h2>Faça o login para continuar</h2>
             <div class="form-floating mb-3">
                <input type="email" class="form-control" id="email" placeholder="Insira o seu e-mail">
                <label for="email">Insira seu e-mail <e-mail></e-mail></label>
             </div>
             <div class="form-floating mb-3">
                <input type="password" class="form-control" id="password" placeholder="Insira a sua senha">
                <label for="password">Insira a sua senha <e-mail></e-mail></label>
             </div>
             <input type="submit" class="btn btn-primary" value="entrar">
~~~