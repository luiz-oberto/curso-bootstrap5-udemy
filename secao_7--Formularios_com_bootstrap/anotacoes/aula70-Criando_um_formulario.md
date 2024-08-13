# Criando um formulário
- Os formulários possuem **diversos inputs no HTML**;
- Consequentemente teremos **váriois componentes no Bootstrap**;
- O interessante é que **temos alguns padrões** que são repetidos entre os componentes, tornando mais fácil o aprendizado;
- Vamos criar um form!

~~~html
<!-- ... -->
<body>
    <!-- Criando form -->
    <div class="col-4 m-4">

        <h2>Formulário de Registro</h2>
        <form>
            <div class="mb-4">
                <label for="email" class="form-label">E-mail</label>
                <input type="email" class="form-control" id="email" name="email" aria-describedby="emailHelp" placeholder="Insira seu e-mail">
                <div id="emailHelp" class="form-text">Não compartilhamos eu endereçõo de e-mail.</div>
            </div>
            <div class="mb-4">
                <!-- para label a classe é form-label -->
                <label for="password" class="form-label">Senha:</label>
                <!-- para input a classe é form control -->
                <input type="password" class="form-control" id="password" name="password" placeholder="Digite sua a senha">
            </div>
            <!-- o Input não deixa colocar HTML dentro dele, como os ícones por exemplo -->
            <!-- <input type="submit" class="btn btn-primary" value="Cadastrar"> -->
             <!-- para isso substiuimos por button -->
             <button type="submit" class="btn btn-primary">Cadastrar</button>
        </form>
    </div>
</body>
<!-- ... -->
~~~