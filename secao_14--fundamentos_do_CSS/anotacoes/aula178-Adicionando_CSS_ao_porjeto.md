# Adicionando CSS ao projeto
- No nosso código html, mais especificamente na tag <head> precisamos acrescentar a tag <link> aonde vamos "linkar" o nosso arquivo CSS no HTML. 
- Fazemos da seguinte maneira
~~~html
    <link rel="stylesheet" type="text/css" href="styles.css">
~~~

- agora no CSS podemos colocar a tag que queremos estilizar junto com seu atributo da seguinte maneira:
~~~css
h1 {
    color: red;
}
~~~