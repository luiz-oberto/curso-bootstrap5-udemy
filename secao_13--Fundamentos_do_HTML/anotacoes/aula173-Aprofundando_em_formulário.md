# Aprofundando em formulário
- Vamos ver os tipos de input mais comuns que vemos nas aplicações
- nos formulários:
    - checkbox
    - date
    - radio
    - textarea (tag para inserção de grandes textos)

~~~html
        <form action="envio.php" method="POST">
            <input type="text" name="name">
            <br> <!--elemento de quebra de linha-->
            <br>
            <input type="checkbox" name="temcarro"> Eu tenho um carro
            <br>
            <br>
            data de nascimento <input type="date" name="aniversario">
            <br>
            <br>
            <input type="radio" name="sexo" value="masculino">Masculino
            <input type="radio" name="sexo" value="feminino">Femenino
            <input type="radio" name="sexo" value="outro">Outro
            <br>
            <br>
            <textarea rows="4" cols="10"></textarea>
            <br>
            <br>
            <input type="password" name="senha">
            <br>
            <br>
            <input type="submit" value="Enviar">
        </form>
~~~