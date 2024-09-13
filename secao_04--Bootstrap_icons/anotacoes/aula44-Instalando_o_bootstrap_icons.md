# Instalando os Ícones
- **Vamos instalar por CDN** pela maior simplicidade;
- Para utilizar os ícones vamos criar uma **tag i**;
- Nesta tag vamos **inserir classes** respectivas para exibir um determinado ícone, ex: **bi bi-x-lg**;
- Estas classes apresentam um ícone de x;
- Podemos utilizar os ícones em menus, botões e em outras partes do site;

No código:
~~~html
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Icons</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <i class="bi bi-bell"></i>
</body>
</html>
~~~

~~~css
/* style.css */
.bi.bi-bell {
    font-size:  40px;
    color: green;
    margin: 20px;
}
~~~