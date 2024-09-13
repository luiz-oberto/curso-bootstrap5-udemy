# Modal
- O **modal** possui dois elemenetos;
- **Um botão** de ativação;
- E **um banner** que aparece após o clique no botão;
- É útil para colocar mensagens ou realizar ações dentro do modal;
- O modal quando construido ele não necessáriamente precisa ficar dentro de um único container

No código
~~~html
    <!-- Modal -->
     <div class="container mb-4">
        <button class="btn btn-info" type="button" data-bs-toggle="modal" data-bs-target="#modal">
            Abrir Modal
        </button>
     </div>

     <!-- container modal -->
      <div class="modal fade" id="modal" tabindex="-1" aria-labelledby="modalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="modalLabel">Este é o título</h5>
                    <button class="btn-close" type="button" data-bs-dismiss="modal" aria-label="close"></button>
                </div>
                <div class="modal-body">
                    <p>Aqui você pode poro qualquer coisa?</p>
                    <p>Tá bom?</p>
                </div>
                <div class="modal-footer"> <!-- Para ações (confirmar, cancelar, fechar)-->
                    <button class="btn btn-secondary" type="button" data-bs-dismiss="modal">
                        Fechar
                    </button>
                    <button class="btn btn-success" type="button">Salvar</button>
                </div>
            </div>
        </div>
      </div>
~~~