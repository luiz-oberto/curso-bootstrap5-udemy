# Popover
- O **popever** é um elemento quue necessita da ação de um botão;
- Ao clicar no botão, **uma área informativa aparece**;
- Precisamos de um **código JS para ativar os popovers**;
- RELEMBRANDO: não esquecer de colocar o atributo **'defer'** na tag de link dos sccripts JS

No código HTML:
~~~html
<!-- index.html -->
    <!-- Pop over -->
    <div class="container mb-4">
        <button 
            class="btn btn-lg btn-success" 
            type="button" 
            data-bs-toggle="popover" 
            title="Este é o título"
            data-bs-content="E aqui podemos inserir a descrição">
                Clique aqui
        </button>
    </div>

    <div class="container mb-4">
        <button 
            class="btn btn-lg btn-danger" 
            type="button" 
            data-bs-toggle="popover" 
            title="Este é o título 2"
            data-bs-content="E aqui podemos inserir a descrição 2">
                Clique aqui
        </button>
    </div>
</body>
~~~


Código JS:
~~~js
var popoverTriggerList = [].slice.call(document.querySelectorAll('[data-bs-toggle="popover"]'),)

var popoverList = popoverTriggerList.map(function(popoverTriggerEl) {
    return new bootstrap.Popover(popoverTriggerEl)
})
~~~