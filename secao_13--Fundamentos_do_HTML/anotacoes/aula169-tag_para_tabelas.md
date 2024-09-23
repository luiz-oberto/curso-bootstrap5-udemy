# Tag para tabelas
- vamos criar um novo arquivo cahmado table.html para separar melhor as aulas
- para criar uma tabela começamos com a tag <table>
- em seguida acrescentamos a tag <tr> (table row)
- agora podemos colocar várias <th> (table head) que vão indicar o título de cada coluna
- agora em outra <tr> vamos colocar as tags <td> (table data), que é onde vamos colocar os dados das tabelas.
- Agora podemos colocar uma 'legenda' para a nossa tabela utilizando a tag <caption>
- Podemos também acrescentar o atributo border a tag <table> com valor "1".

~~~html
        <table border="1">
            <caption>Estoque de roupas</caption>
            <tr>
                <th>Nome produto</th>
                <th>tamenho</th>
                <th>cor</th>
            </tr>
            <tr>
                <td>Camisa</td>
                <td>p</td>
                <td>azul</td>
            </tr>
            <tr>
                <td>calça</td>
                <td>2</td>
                <td>preta</td>
            </tr>
            <tr>
                <td>jaqueta</td>
                <td>g</td>
                <td>marrom</td>
            </tr>
        </table>
~~~

