# Validações
- O Bootstrap também nos dá possibilidade de **criar validações**;
- Vamos precisar inserir algumas **classes de validação**;
- Informar um feedback para o que está certo e o que está errado;
- E também **observar o envio do formulário**, para poder ativar a validação antes que isso ocorra;

- Para esta aula vamos utilzar outra pasta para armazenar nossos scripts *html* e *js*, nesse caso a pasta validacao vai servir para armazenar esses dois scripts.

Código HTML:
~~~html
<!-- validacoes/index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulários</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="css/styles.css">
    <script src="js/scripts.js" defer></script>
</head>
<body>

    <!-- Validação Bootstrap -->
     <div class="container">
        <div class="row justify-content-center m-4">
            <div class="col-6">
                <h2>Faça o login para continuar:</h2>
                <form class="row needs-validation" novalidate>
                    <div class="col-12 mb-4">
                        <label for="email" class="form-label">E-mail:</label>
                        <input type="email" class="form-control" id="email" placeholder="Digite seu e-mail" required>
                        <div class="valid-feedback">
                            Ok
                        </div>
                    </div>
                    <div class="col-12 mb-4">
                        <label for="password" class="form-label">Senha:</label>
                        <input type="password" class="form-control" id="password" placeholder="Digite a sua senha" required>
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

</body>
</html>
~~~

Código JS
~~~js
// validacoes/js/scripts.js
(function() {

    'use strict'

    var forms = document.querySelectorAll('.needs-validation');

    Array.prototype.slice.call(forms)
        .forEach(function (form) {
            form.addEventListener('submit', function(event) {

                if(!form.checkValidity()) {
                    event.preventDefault();
                    event.stopPropagation();
                }

            form.classList.add('was-validated');

            }, false);

        });

})()
~~~