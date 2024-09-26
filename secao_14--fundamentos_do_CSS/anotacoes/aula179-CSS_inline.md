# CSS inline
- Nesta aula vamos falar sobre a maneira errada de se inserir CSS
- podemos usar uma tag HTML da seguinte forma 
~~~html
<p style="color: blue"></p>
~~~
- Porém, se tivermos várias tags que precisarmos mudar a cor, do jeito que fizemos iria ter que fazer em todas as outras tags, fora que se estilizarmos através do CSS a cor que vai prevalecer vai ser o que está no HTML

~~~css
p {
    color: green;
}
~~~