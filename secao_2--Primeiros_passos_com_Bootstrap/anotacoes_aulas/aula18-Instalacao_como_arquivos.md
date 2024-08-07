# Instalação com arquivos
- Para instalar com arquivos no nosso servidor, precisamos *Fazer o download do Bootstrap*
- Os arquivos estão disponíveis no site oficial;
- Colocaremos os arquivos em *diretórios do nosso projeto*
- e *realizamos o link de CSS e JavaScript*, a partir dos caminhos relativos;
- Vamos lá!

1. Vamos até a  documentação do bootstrap e clicar em Download de *Compliled CSS e  JS*
2. Feito isso, extraia a pasta e vá nas pastas css e js e puxe os seguintes arquivos para dentro do seu projeto respecivamente;
    - bootstrap.css
    - bootstrap.js
3. Feito isso, vamos ajustar nosso index.html para deixar da seguinte forma:
~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Arquivos</title>
    <link rel="stylesheet" href="css/bootstrap.css">
</head>
<body>
    <h1>Testando Bootstrap por arquivos</h1>
    <script src="js/bootstrap.js"></script>
</body>
</html>
~~~
4. Feito isso podemos abrir nossa apllicação com o liveserver e observar as diferenças que ele vai paresentar em relação ao html puro.