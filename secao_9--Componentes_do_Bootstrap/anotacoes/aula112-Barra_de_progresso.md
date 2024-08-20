# Progres
- O **Progress** é um componente para barra de progresso;
- Que vai se completando a medida da **alteração de um atributo**;
- Pode ser utilizado para **loading** ou **upload de arquivos**;
- RECOMENDA-SE  LER  A DOCUMENTAÇÃO DESTE COMPONENTE.

No código:
~~~html
    <!-- Progress -->
     <div class="container mb-4">
        <div class="progress mb-4">
            <div 
                class="progress-bar" 
                role="progressbar" 
                aria-valuenow="0" 
                aria-valuemin="0" 
                aria-valuemax="100"
                >
            </div>
        </div>
        <div class="progress mb-4">
            <div 
                class="progress-bar" 
                role="progressbar" 
                style="width: 25%"
                aria-valuenow="25" 
                aria-valuemin="0" 
                aria-valuemax="100"
                >
            </div>
        </div>
        <div class="progress mb-4">
            <div 
                class="progress-bar" 
                role="progressbar" 
                style="width: 50%"
                aria-valuenow="50" 
                aria-valuemin="0" 
                aria-valuemax="100"
                >
            </div>
        </div>
        <div class="progress mb-4">
            <div 
                class="progress-bar bg-success" 
                role="progressbar" 
                style="width: 75%"
                aria-valuenow="75" 
                aria-valuemin="0" 
                aria-valuemax="100"
                >
            </div>
        </div>
        <div class="progress mb-4">
            <div 
                class="progress-bar bg-danger" 
                role="progressbar" 
                style="width: 85%"
                aria-valuenow="85" 
                aria-valuemin="0" 
                aria-valuemax="100"
                >
            </div>
        </div>
        <div class="progress mb-4">
            <div 
                class="progress-bar progress-bar-striped bg-warning" 
                role="progressbar" 
                style="width: 95%"
                aria-valuenow="95" 
                aria-valuemin="0" 
                aria-valuemax="100"
                >
            </div>
        </div>
        <div class="progress mb-4">
            <div 
                class="progress-bar progress-bar-striped bg-success" 
                role="progressbar" 
                style="width: 100%"
                aria-valuenow="100"
                aria-valuemin="0" 
                aria-valuemax="100"
                >
            </div>
        </div>
~~~
- Perceba que podemos alterar o estilo da progress-bar na sua classe e que ela cresce alterando os valores de largura (width) e o valor atual (aria-valuenow)