# Badges
- O componente **Badge** serve para exibir alguma **informação ao lado de texto**;
- Como **label**, exemplo: produtos novos (new);
- Ou **notificações**, com número, exemplo: Mensagens 9;

No código:
~~~html
    <!-- Badge -->
     <div class="col-4 m-4">
        <h1>
            Cadeira Gamer X400 
            <span class="badge bg-primary">New</span>
        </h1>
        <h1>
            Fone de ouvido XY710
            <span class="badge bg-warning">10% off</span>
        </h1>
        <button type="button" class="btn btn-dark">
            Mensagens <span class="badge bg-success">4</span>
        </button>
        <button type="button" class="btn btn-dark">
            Mensagens <span class="badge bg-info">4</span>
        </button>
     </div>
~~~