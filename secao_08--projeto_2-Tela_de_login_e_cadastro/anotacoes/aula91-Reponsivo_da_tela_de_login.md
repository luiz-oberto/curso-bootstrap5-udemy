# Responsivo da tela de login
Nessa aula vamos adaptar nosso sistema para dispositivos mobile

- Começando pelo tamanho mínimo que nosso formulário vai ocupar

~~~css
/* ... */
@media(min-width: 768px) {
    #from-container {
        margin: 50px auto;
        padding: 50px;
    }
}
/* ... */
~~~

- Ajuste do tamanho do botão para o mobile
~~~css
/* Ajustando o botão para MOBILE */
.btn.btn-primary {
    width: 100%;
}

@media(min-width: 768px) {
    .btn.btn-primary {
        width: auto;
    }
}
/* ###################### */
~~~

- E ajuste de padding de imagem
~~~css
/* ajustando o padding da imagem */
.col-md-6.order-md-1 {
    padding-top: 50px;
}

@media(min-width: 768px) {
    .col-md-6.order-md-1{
        padding-top: 0;
    }
}
~~~