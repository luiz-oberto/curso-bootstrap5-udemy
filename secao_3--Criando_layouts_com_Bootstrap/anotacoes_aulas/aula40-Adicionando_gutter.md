# Gutters
- Os **Gutters** são intervalos quue podemos inserir entre as colunas;
- É possível inserri no **eixo x ou y**;
- Exemplo: **gx-2** (horizontal);
- Ou: **gy-4** (vertical);
- Os números que utilizamos são **baseados e rem da página**, fonte do elemento root;
- O número **3 é a referência para 1rem**;

No código:
~~~html
    <!-- Gutters -->
    <div class="container" id="gutter">
        <div class="row gx-2">
            <div class="col">
                <p>GX</p>
            </div>
            <div class="col">
                <p>GX</p>
            </div>
        </div>

        <div class="row gy-4">
            <div class="col">
                <p>GY</p>
            </div>
            <div class="col">
                <p>GY</p>
            </div>
        </div>

        <div class="row g-5">
            <div class="col-6">
                <p>G</p>
            </div>
            <div class="col-6">
                <p>G</p>
            </div>
            <div class="col-6">
                <p>G</p>
            </div>
            <div class="col-6">
                <p>G</p>
            </div>
        </div>
    </div>
~~~

~~~css
/* Gutter */
#gutter .row {
    height: 200px;
}

#gutter .col-6 {
    margin: auto;
    height: 50px;
}

.row p {
    border: 2px  solid green;
}
~~~