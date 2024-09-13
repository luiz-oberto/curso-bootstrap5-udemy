# Validações do HTML
- O Bootstrap funciona também com a **validação padrão do HTML**
- Onde os **atributos são utilizados** para dizer se um dados está errado ou não;
- OBS: vamos continuar utilizando nesta aula o index.html de **validacoes**

No código:

~~~html
         <!-- Validação HTML -->
         <div class="container">
            <div class="row justify-content-center m-4">
                <div class="col-6">
                    <h2>Faça o login para continuar:</h2>
                    <form class="row needs-validation">
                        <div class="col-12 mb-4">
                            <label for="email" class="form-label">E-mail:</label>
                            <input type="email" class="form-control" id="email" placeholder="Digite seu e-mail" required>
                            <div class="valid-feedback">
                                Ok
                            </div>
                        </div>
                        <div class="col-12 mb-4">
                            <label for="password" class="form-label">Senha:</label>
                            <input type="password" class="form-control" id="password" placeholder="Digite a sua senha" required minlength="5">
                            <div class="valid-feedback">
                                Ok
                            </div>
                        </div>
                        <div class="col-12 mb-4">
                            <button class="btn btn-primary" type="submit">Entrar</button>
                        </div>
                    </form>
                </div>
            </div>
         </div>
~~~