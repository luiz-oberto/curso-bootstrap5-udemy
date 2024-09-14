# Clearfix
- **Clearfix** é uma forma de resetar o float
- No CSS moderno **não utilizamos muito o float**
- Porém em algum **projeto mais antigo** podemos encontrar esta regra;
- Se não utilizamos o clear, **os elementos quebram na tela**;
- O Bootstrap nos oferece uma fáccil solução para isso;

~~~html
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Helpers</title>
    <link rel="stylesheet" href="css/styles.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>
    <!-- COM FIX -->
    <div class="clearfix mt-4">
        <div class="box float-end"></div>
    </div>
    <div class="box"></div>
    <!-- SEM FIX -->
    <div class="box float-end"></div>
    <div class="box"></div>
</body>
</html>
~~~

~~~css
/* styles.css */
body {
    padding-bottom: 1000px;
}

.box {
    background-color: red;
    height: 50px;
}

.box.float-end {
    background-color: blue;
    width: 50px;
}
~~~