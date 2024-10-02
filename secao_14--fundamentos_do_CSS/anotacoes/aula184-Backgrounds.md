# backgrounds
- vamos criar um arquivo chamado background.html e inserir o seguinte código:

~~~html
<!-- backgrounds.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Background CSS</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <div class="div-background">
        <h1 class="titulo-background">Este é o reino dos backgrounds</h1>
    </div>
</body>
</html>
~~~

no style.css:
~~~css
/* Backgrounds */
.div-backgrounds  {
    background-image: url('img/por-do-sol.jpg');
    height: 300px;
}

.titulo-background {
    text-align: center;
    background-color: #000;
    color: #fff;
}
~~~