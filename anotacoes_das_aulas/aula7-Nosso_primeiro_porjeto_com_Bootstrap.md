# Nosso primeiro primeiro projeto com Bootstrap
- Nesta aula vamos criar nosso *Primeiro projeto com Bootstrap
- Instalaremos por meio do *CDN*
- CDN é um seridor que distribui geralmente arquivos esticos em cache, *carregando de maneira mais rápida* no nosso projeto;
- Há *prós e contras* em usar o CDN;
- Vamos a instalação.

1. Vamos começar criando um index.html
2. Em seguida vamos criar com "!" nosso esqueleto o HTML
3. Na head, vamos colocar o link que "importa" o nosso Bootstrap 5, que é o seguinte link:
~~~html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
~~~

4. por fim, vamos deixar noss index.html dessa maneira:
~~~html
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Bootstrap -->
     <!-- Esse link ns traz o Bootstrap 5 direto do site oficial -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <title>Bootstrap</title>
</head>
<body>
    <h1>Hello Word Bootstrap</h1>
</body>
</html>

~~~