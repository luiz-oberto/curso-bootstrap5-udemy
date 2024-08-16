# Accordion
- O **accordion** é uma lista com elementos  ocultos;
- **Ao clicar no título** de cada item da lista, uma descrição é exibida;
- Enquanto isso **o outro item que estava aberto, é fechado**;
- Este componente é interessante quando precisamos **poupa espaço**;

No código:
~~~html
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Componentes</title>
    <link rel="stylesheet" href="css/styles.css">
    <!-- CSS only -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <!-- Javascript Bundle withh Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"
        defer></script>
</head>

<body>
    <!-- Accordion -->
    <div class="col-4 m-4">
        <h2>Accordion</h2>
        <div class="accordion" id="accordion">
            <div class="accordion-item">
                <h2 class="accordion-header" id="headingOne">
                    <button class="accordion-button" type="button" data-bs-toggle="collapse"
                        data-bs-target="#collapseOne"
                        aria-expanded="true"
                        aria-controls="collapseOne">
                        item 1
                    </button>
                </h2>
                <div class="accordion-collapse collapse show" 
                id="collapseOne" 
                aria-labelledby="headingOne"
                data-bs-parent="#accordion"
                >
                <div class="accordion-body">
                    <p>Este é o item 1 e sua descrição</p>
                </div>
                </div>
            </div>
            <!-- accordion 2 -->
            <div class="accordion-item">
                <h2 class="accordion-header" id="headingTwo">
                    <button class="accordion-button" 
                        type="button" 
                        data-bs-toggle="collapse"
                        data-bs-target="#collapseTwo"
                        aria-expanded="true"
                        aria-controls="collapseTwo">
                        item 2
                    </button>
                </h2>
                <div class="accordion-collapse collapse" 
                id="collapseTwo"
                aria-labelledby="headingTwo"
                data-bs-parent="#accordion"
                >
                <div class="accordion-body">
                    <p>Este é o item 2 e sua descrição</p>
                </div>
                </div>
            </div>
            <!-- accordion 3 -->
            <div class="accordion-item">
                <h2 class="accordion-header" id="headingThree">
                    <button class="accordion-button" type="button" data-bs-toggle="collapse"
                        data-bs-target="#collapseThree"
                        aria-expanded="true"
                        aria-controls="collapseThree">
                        item 3
                    </button>
                </h2>
                <div class="accordion-collapse collapse" 
                id="collapseThree" 
                aria-labelledby="headingThree"
                data-bs-parent="#accordion"
                >
                <div class="accordion-body">
                    <p>Este é o item 3 e sua descrição</p>
                </div>
                </div>
            </div>
        </div>
    </div>
</body>

</html>
~~~