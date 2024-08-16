# Breadcrumb
- Este componente serve para mostrar ao usuário **o caminho que já pecorreu no site**;
- Podemos mostrar as **páginas principais**;
- Desta maneira ele consegue **voltar para as anteriores**;
- "migalhas de pão" (rastro de por onde navegou)

No código:
~~~html
      <div class="container">
        <nav aria-label="breadcrumb">
            <ol class="breadcrumb">
                <li class="breadcrumb-item"><a href="#">Home</a></li>
                <li class="breadcrumb-item"><a href="#">Catálogo</a></li>
                <li class="breadcrumb-item active" aria-current="page">Página de produto</li>
            </ol>
        </nav>
        <h2>Página de Produto</h2>
        <p>Descrição do produto</p>
      </div>
~~~