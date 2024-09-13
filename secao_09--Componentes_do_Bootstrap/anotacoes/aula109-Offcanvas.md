# Offcanvas
- Offcanavas é **parecido com o Modal**;
- Um **conteudo que fica oculto**, a espera de um botão;
- Porém tem uma perspectiva diferente, **costuma aparecer pela lateral**;
- Interessante para carrinhos de e-commerce, por exemplo;

No código:
~~~html
    <!-- Off canvas -->
     <div class="container m-4">
        <button 
            class="btn btn-primary" 
            type="button" 
            data-bs-toggle="offcanvas" 
            data-bs-target="#offcanvasRight" 
            aria-controls="offcanvasRight"
            >
            Abrir carrinho
            </button>

            <div class="offcanvas offcanvas-end" 
                tabindex="1"
                id="offcanvasRight"
                aria-labelledby="OffcanvasLabel">
                <!-- offcanvas-end -> é uma variação do offcanvas -->
                 <div class="offcanvas-header">
                    <h5 class="offcanvasLabel">Carrinho</h5>
                    <button 
                        class="btn-close text-reset"
                        type="submit" 
                        type="button"
                        data-bs-dismiss="offcanvas"
                        aria-label="Close"></button>
                 </div>
                 <div class="offcanvas-body">
                    <ul>
                        <li>Produto 1</li>
                        <li>Produto 2</li>
                        <li>Produto 3</li>
                    </ul>
                 </div>
            </div> 
     </div>
~~~

### button.text-reset
- Mudar a cor do botão