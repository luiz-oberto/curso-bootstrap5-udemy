# Inserindo nosso CSS
- O estilo do Bootstrap pode não ser suficiente para finalizar uma aplicação, *então inserindo nosso CSS*;
- Vamos *linkar sempre abaixo do BS*;
- Nossas *Regras precisam ter um nível de seleção pelo menos igual* o do BS para substituí-la;;
- Vamos a prática!

vamos criar nosso index.html deixando da seguinte forma:
~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <h1>Seção de Layout</h1>
    <button class="btn btn-primary">Clique em mim</button>
</body>
</html>
~~~

agora vamos criar uma pasta css com o arquivo style.css e colcoar as seguuintes coisas dentro do arquivo .css:
~~~css
h1 {
    color: red;
}

.btn-primary {
    background-color: red;
}
~~~

- Note que, para mudar a cor do botão é necessário que especifiuue sua classe, não apenas o botão, senão não ocorrerá mudanças.