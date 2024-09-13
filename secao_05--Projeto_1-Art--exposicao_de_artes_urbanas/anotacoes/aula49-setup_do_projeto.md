# Setup do projeto
- Nesta aula vamos montar o setup do bootstrap para o nosso projeto
- Nele vamos precisar  dos seguintes elementos:
    1. o CDN do bootstrap (link de referência)
    2. Os icones (link de referencia aos icones do bootdtrap)
    3. o caminho para o arquivo css (css/style.css)
    4. O favicon do nosso site que vai aparecer no guia do navegador

- Nosso código ficará assim:
~~~html
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Art</title>
    <!-- Favicon -> é o ícone que fica ao lado do nome do site na aba de título -->
    <link rel="shortcut icon" href="img/favicon.ico" type="image/x-icon">
    <!-- CSS Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <!-- Bootstrap icones -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <!-- CSS do Art -->
     <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <h1>Testando bootstrap</h1> <i class="bi bi-x-lg"></i>
</body>
</html>
~~~
- E colocaremos o css para testar se está tudo funcionando
~~~css
h1 {
    color: red;
}
~~~