# Iniciando com formulários
- para fazermos um formulários utilizamos a tag <form>
- nela temos o atributo **action** que é aonde vamos enviar as informações, é necessário que esse atributo sempre esteja preenchido corretamente em conjunto com o backend senão o formulário não vai ser enviado para nenhum lugar
- o segundo atributo é o **method** que recebe valores GET ou POST
    - GET: Utilizado quando vamos receber dados, ou seja, o sistema vai buscar no banco de dados informações que nós solicitamos para ele (buscas, pesquisas no banco de dados)
    - POST: Envio de informações para salvar no banco de dados

- dentro dos Forms utilizamos a tag <input> que são os campos que vão conter as informações
- dentro dela temos os atributos *type* e *name*
    - type: tipo do input (tipo text)
    - name: serve para falar pro backend o que vamos salvar no banco, referenciar as informções

- Temos que ter também o botão de 'enviar' para concluir e enviar as informações do formulário


~~~html
        <form action="envio.php" method="POST">
            <input type="text" name="name">
            <br> <!--elemento de quebra de linha-->
            <input type="submit" value="Enviar">
        </form>
~~~