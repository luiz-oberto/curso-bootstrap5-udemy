# Tooltip
- O **Tooltip** é um componente de "dica";
- Onde podemos oferecer **informações em algum elemento**;
- Vamos precisar de um código **JavaScript parar ativar**;

No código:
~~~html
<!-- index.htmk -->
     <!-- Tooltip -->
      <div class="container">
        <button class="btn btn-secondary" type="button" data-bs-toggle="tooltip" data-bs-placement="top" title="Aqui vai uma dica!">Este botão tem tooltip</button>
      </div>
~~~

No JS:
~~~js
// scripts.js
// código para uso do tooltip
var tooltipTriggerList = [].slice.call(document.querySelectorAll('[data-bs-toggle="tooltip"]'),)

var tooltipList = tooltipTriggerList.map(function(tooltipTriggerEl) {
    return new bootstrap.Tooltip(tooltipTriggerEl)
})
~~~