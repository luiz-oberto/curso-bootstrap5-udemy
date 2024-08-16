# Alertas
- Os componentes de alerta servem para **exibir mensagens**;
- Temos **diversar cores disponíveis**, sinalizando cada ação possível;
- Como: erros, confirmações, informções e etc;
- Estas mensagens são como **feedbacks** do sistema para o usuário final;

No código:
~~~html
    <!-- Alertas -->
     <div class="col-6 m-4">
        <div class="alert alert-primary" role="alert">
            Esta é uma mensagem comum do sistema!
        </div>
        <div class="alert alert-success" role="alert">
            Usuário cadastrado com sucesso!
        </div>
        <div class="alert alert-danger" role="alert">
            Não foi possível fazer o login
        </div>
        <!-- com Link -->
        <div class="alert alert-warning" role="alert">
            Não encontramos o seu pedido, faça uma solicitação <a href="" class="alert-link">clicando aqui</a>. Responderemos o quanto antes.
        </div>
        <!-- com mais conteúdo -->
        <div class="alert alert-success" role="alert">
            <h4 class="alert-heading">Pedido relizado!</h4>
            <p>Recebemos o seu pedido, e já estamos preparando para o envio</p>
            <hr>
            <p class="mb-0">Caso você precis de mais alguma informação, entre em contato <a href="" class="alert-link">clicando aqui</a></p>
        </div>
        <!-- com  ícone de fechar -->
         <div class="alert alert-warning alert-dismissible fade show" role="alert">
            <strong>Ops!</strong> Aconteceu algo errado no sistema
            <button 
            type="button" 
            class="btn-close" 
            data-bs-dismiss="alert"
            aria-label="close"
            ></button>
         </div>
     </div>
~~~