# Layout com forms
- Os conhecimentos que aprendemos na **seção de Layout** são úteis em formulários;
-Podemos condicionar a **exibição dos inputs pelo grid** de colunas;
- Ou seja, há uma forma fácil de **inserir inputs em uma linha**;
- E também de diferentes larguras;

No código:
~~~html
    <!-- Layouts com forms -->
    <div class="container col-6 mb-4">
        <h2>Cadastre-se preechendo o formulário:</h2>
        <form class="row g-3">
            <div class="col-md-6">
                <label for="email" class="from-label">Email:</label>
                <input type="email" class="form-control" id="email" placeholder="digite o seu e-mail">
            </div>
            <div class="col-md-6">
                <label for="password" class="from-label">Senha:</label>
                <input type="password" class="form-control" id="password" placeholder="digite a  sua senha">
            </div>
            <div class="col-md-4">
                <label for="centavos" class="form-label">CEP:</label>
                <input type="text" class="form-control" placeholder="Digite o seu CEP">
            </div>
            <div class="col-md-10">
                <label for="rua" class="form-label">Rua:</label>
                <input type="text" class="form-control" id="rua" placeholder="Digite a sua">
            </div>
            <div class="col-md-2">
                <label for="numero" class="form-label">Numero:</label>
                <input type="text" class="form-control" id="numero" placeholder="Nº">
            </div>
            <div class="col-md-4">
                <label for="cidade" class="form-label">Cidade:</label>
                <input type="text" class="form-control" id="cidade" placeholder="Sua cidade">
            </div>
            <div class="col-md-4">
                <label for="estado" class="form-label">Estado:</label>
                <select name="estado" id="estado" class="form-select">
                    <option selected>Escolha</option>
                    <option value="1">...</option>
                </select>
            </div>
            <div class="col-md-4">
                <label for="UF" class="form-label">UF:</label>
                <select name="UF" id="UF" class="form-select">
                    <option selected>Escolha</option>
                    <option value="PA">PA</option>
                    <option value="SP">SP</option>
                    <option value="DF">DF</option>
                </select>
            </div>
            <div class="col-12">
                <div class="form-check">
                    <input type="checkbox" class="form-check-input" id="newsletter">
                    <label for="newsletter" class="form-check-label">
                        Receber newsletter?
                    </label>
                </div>
            </div>
            <div class="col-12">
                <button type="submit" class="btn btn-primary">Cadastrar</button>
            </div>
        </form>
    </div>
~~~