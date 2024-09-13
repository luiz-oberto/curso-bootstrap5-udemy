# Estrutura da página de login
Vamos aproveitar esta aula pra rever alguns conceitos que já estudamos aqui, segue o código do login.html:

~~~html
    <div class="container col-11 col-md-9" id="form-container">
        <div class="row align-items-center gx-5">
            <div class="col-md-6 order-md-2">
                <h2>Faça o login para continuar</h2>
                <form>
                    <div class="form-floating mb-3">
                        <input type="email" class="form-control" id="email" name="email" placeholder="Digite o seu e-mail">
                        <label for="email" class="form-label">Digite o seu e-mail</label>
                    </div>
                    <div class="form-floating mb-3">
                        <input type="password" class="form-control" id="password" name="password" placeholder="Digite a sua senha">
                        <label for="password" class="form-label">Digite a sua senha</label>
                    </div>
                    <input type="submit" class="btn btn-primary" value="Entrar">
                </form>
            </div>
            <div class="col-md-6 order-md-1">
                <div class="col-12">
                    <img src="img/sign_in.svg" alt="Entrar no Sistema" class="img-fluid">
                </div>
                <div class="col-12" id="link-container">
                    <a href="register.html">Ainda não tenho cadastro</a>
                </div>
            </div>
        </div>
    </div>
~~~

### .col-11.col-md-9
- Nessa classe nós falamos para nosso código como se comportar de acordo com as varições de resoluções
- nesse exemplo ele vai ocupar 11 colunas quando estiver em desktop e 9 quando no celular

### .row.align-items-center
- a row é criada geralmente dentro de um container, ela é como uma 'linha'
- align-items-center -> vai centralizar ao centro todos os itens nela contidos

### .form-floating
- Form-floating é um tipo de classe que nos ajuda a manter uma label dentro de um input, lembra do formulário de logindo google que quando você clica no input as letras dentro do input flutuam pra cima? senão lembra basta executar esse código da aula e ver você mesmo.

### .btb.btn-primary
- nosso clássico botão azul para confirmarmos nosso formulário.

### .order-md-1
- O '.order' nos ajuda a ordernar nossas divs do jeito qu quisermos, nesse caso utilizamoso breakpoint md-*, de acordo com exemplo passado, a imagem da tela de login vai estar na esquerda (como se viesse primeiro) enquanto a ressolução for maior ou igual a 768px. Quando a resolução for menor que esse tamanho a imagem da tela de login vai aparecer em baixo do formulário que criamos.
- É como se dissesse: "priorize a imagem enquanto a resolução for maior que 768px" (**.order-md-1**).

