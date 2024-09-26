# Internal CSS
- Essa forma é também outra forma errada de se adicionar CSS
- essa forma se utiliza da tag <style></style> posicionada dentro da tag <head>
- utilizar o CSS dessa maneira causa uma mistura de código tanto HTML como CSS em um mesmo arquivo, o que não deixa as coisas práticas nem fáceis de se entender
exemplo:

~~~html
    <style type="text/css">
        p {
            color: gray;
        }
    </style>
~~~