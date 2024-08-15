# CSS da página de login
Nesta aual vamos trabalhar na estilização do nosso form de login.

segue o código do CSS:
~~~CSS
body {
    background-color: #F8F8F8;
}

/* FORM */
#form-container {
    /* cor de fundo */
    background-color: #FFF;
    /* arrendondamento das bordas */
    border-radius: 20px;
    /* sombreamento da caixa (dando a sensação de que está flutuando) */
    box-shadow: .5px  10px 15px rgba(0, 0, 0, .2);
    /* margem da borda */
    margin: 25px auto;
    /* espaçamento interno do nosso container */
    padding: 25px;
}

#form-container h2 {
    /* deixar em negrito (bem negrito) */
    font-weight: 900;
    /* margem da base */
    margin-bottom: 30px;
}

/* Estilizando o link */
#form-container a {
    /* cor da donte de link */
    color: #222;
    /* transição */
    transition: .5s;
}

#form-container a:hover {
    /* cor para a qual vai mudar quando o mouse passar em cima */
    color: #6c63ff;
}

#form-container form {
    padding-bottom: 0px;
}

/* tirando as bordas do nossos inputs */
#form-container .form-control {
    border: none;
    border-bottom: 1px solid #ccc;
    border-radius: 0;
}

/* tirando o focus que ocorre ao clicarmos no nosso input */
#form-container .form-control:focus {
    box-shadow: none;
}

/* deixando as palavras de dentro da nossa label mais claras */
#form-container .form-floating label {
    color: #ccc;
}

/* e deixando mais escuro quando o ocorrer o evento de focus */
#form-container .form-floating > .form-control:focus~label {
    color: #222;
}

/* mudando a cor do Botão */
#form-container input[type="submit"] {
    background-color: #6c63ff;
    border-color: #6c63ff;
}

/* IMAGE */
.row.align-items-center {
    align-content: center;
    height: 100%;
    padding: 50px 0;
}

/* Centralizando link */
#link-container  {
    text-align: center;
    padding-top: 50px;
}
~~~