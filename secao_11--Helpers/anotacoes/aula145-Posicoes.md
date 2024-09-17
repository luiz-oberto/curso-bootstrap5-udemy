# Posições
- Temos um helper para **definir posições também**;
- Podemos por meio de classes **fixar elementos no topo ou no rodapé** da tela;
- **Menos regras de CSS para gerenciarmos**, apenas classes;
- o Sticky sempre vai partir do ponto em foi colocado no html

~~~~html
<!-- no início do body -->
    <!-- POSIÇÃO STIKY -->
    <div class="sticky-top box-sticky"></div>
<!-- final do body -->
    <!-- POSIÇÃO FIXA -->
    <div class="fixed-bottom box-fixed"></div>
~~~~

~~~~css
.box-sticky,
.box-fixed {
    width: 100px;
    height: 100px;
    background-color: green;
}

.box-fixed {
    background-color: blueviolet;
}
~~~~