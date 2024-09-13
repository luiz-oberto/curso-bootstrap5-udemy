# Somente Leitura
- O **readonly** é um atributo que indica somente leitura;
- Temos duas formas de apresentação no Bootstrap:
    - **Atributo**: colocamos o atriuto readonly e o input recebe os estilos do componente
    - **Classe do BS**: o input fica parecendo apenas um texto;
- obs: readonly é uma forma de enviar os dados para o servidor, já o disabled não envia!

No código
~~~html
    <!-- Read Only -->
    <div class="col-4 m-4">

        <h2>Formulário de Read Only</h2>
        <form>
            <div class="mb-4">
                <label for="email" class="form-label">E-mail</label>
                <input type="email" class="form-control" id="email2" name="email2" placeholder="Insira seu e-mail" readonly value="matheus@email.com">
            </div>
            <div class="mb-4">
                <label for="email" class="form-label">E-mail</label>
                <input type="email" class="form-control-plaintext" id="email3" name="email3" placeholder="Insira seu e-mail" value="matheus@email.com" readonly>
            </div>

             <button type="submit" class="btn btn-primary">Cadastrar</button>
        </form>
    </div>
~~~