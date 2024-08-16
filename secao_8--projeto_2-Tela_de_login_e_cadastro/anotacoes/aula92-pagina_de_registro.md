# Página de Registro
Nesta aula vamos fazer nosso formulário de regitro para concluir este módulo.

Como já fizemos a maior parte da estilização para o formulário de login, fazer o formulário de registro não dará tanto trabalho porque podemos reaproveitar todo o estilo feito para o login. Dito isso, vamos aos códigos:

~~~html
<!-- register.html -->
   <div class="container col-11 col-md-9" id="form-container">
        <div class="row gx-5">
            <div class="col-md-6">
                <h2>Realize seu cadastro</h2>
                <form>
                    <div class="form-floating mb-3">
                        <input type="text" class="form-control" id="name" name="name" placeholder="Digite o seu nome">
                        <label for="name" class="form-label">Digite o seu nome</label>
                    </div>
                    <div class="form-floating mb-3">
                        <input type="text" class="form-control" id="lastname" name="lastname" placeholder="Digite o seu sobrenome">
                        <label for="lastname" class="form-label">Digite o seu sobrenome</label>
                    </div>
                    <div class="form-floating mb-3">
                        <input type="email" class="form-control" id="email" name="email" placeholder="Digite o seu e-mail ">
                        <label for="email" class="form-label">Digite o seu e-mail</label>
                    </div>
                    <div class="form-floating mb-3">
                        <input type="password" class="form-control" id="password" name="password" placeholder="Digite a sua senha">
                        <label for="password" class="form-label">Digite a sua senha</label>
                    </div>
                    <div class="form-floating mb-3">
                        <input type="password" class="form-control" id="confirmpassword" name="confirmpassword" placeholder="Confirme a sua senha">
                        <label for="confirmpassword" class="form-label">Confirme a sua senha</label>
                    </div>
                    <div class="mb-3">
                        <div class="form-check mb-2">
                            <input type="checkbox" class="form-check-input" value="" id="agree-form" name="agree-form">
                            <label for="agree-form" class="form-check-label">
                                Você aceita os <a href="#">termos de serviço</a>
                            </label>
                        </div>
                        <div class="form-check mb-2">
                            <input type="checkbox" class="form-check-input" checked id="newsletter" name="newsletter">
                            <label for="newsletter" class="form-check-label">
                                Deseja receber as nossas Newsletter?
                            </label>
                        </div>
                        <input type="submit" class="btn btn-primary" value="Cadastrar">
                    </div>
                </form>
            </div>
            <div class="col-md-6">
                <div class="row align-items-center">
                    <div class="col-12">
                        <img src="img/hello.svg" alt="Tela de Registro" class="img-fluid">
                    </div>
                    <div class="col-12" id="link-container">
                        <a href="login.html">Eu já tenho uma conta</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
~~~

- Alterações feitas no CSS:
    - foi acrescentado a mudança de cor no checkbox apenas quando ele for marcado
    - e uma pequena margem ao botão de para separar um pouco do formulário
~~~css
/* mudando a cor do Botão */
#form-container input[type="submit"],
#form-container input[type="checkbox"]:checked {
    background-color: #6c63ff;
    border-color: #6c63ff;
}

/* Ajustando o botão para MOBILE */
.btn.btn-primary {
    width: 100%;
    margin-top: 25px;
}

~~~