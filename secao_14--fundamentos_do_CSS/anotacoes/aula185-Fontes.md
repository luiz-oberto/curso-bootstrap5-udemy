#  Fontes
- Vamos criar mais arquivo dessa vez com o nome fontes.html e inserir os seguintes códigos para testar alguns tipos de fontes

~~~html
<!-- fontes.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Background CSS</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <div>
        <p class="family">Aqui é sobre as famílias</p>
        <p class="family serif">Aqui é sobre as famílias</p>
        <p class="family sans-serif">Aqui é sobre as famílias</p>
        <p class="family monospace">Aqui é sobre as famílias</p>
        <p class="family italic">Aqui é sobre os styles</p>
        <p class="family oblique">Aqui é sobre os styles</p>
        <p class="family bold">Aqui é sobre os weight</p>
        <p class="family variant">Aqui é sobre os variants</p>
    </div>
</body>
</html>
~~~

- no style.css podemos utilizar as classes da seguinte maneira:
~~~css
/* Fontes */
.family {
    color: #000;
    font-size: 40px;
}

/* editando duas classes */
.family.serif {
    color: green;
}

.serif {
    font-family: "times new roman";

}

.sans-serif {
    font-family: arial;
}

.monospace {
    font-family: "Courier New";
}

.italic {
    font-style: italic;
}

.oblique {
    font-style: oblique;
}

.bold {
    font-weight: bold;
}

.variant {
    font-variant: small-caps;
}
~~~