# Box model: padding

~~~css
.boxmodel {
    width: 200px;
    height: 200px;
    background-color: red;
    /* geral */
    padding: 20px;

    /* específico */
    padding-top: 30px;
    padding-left: 10px;
    padding-right: 20px;
    padding-bottom: 5px;

    /* específico agrupado */
    /* adicionando  padding no sentido horário */
    padding: 30px 20px 5px 10px;

    /* específico agrupado - 3 medidas - top, right-left, bottom*/
    padding: 30px 20px 5px;

    /* específico agrupado - 2 medidas - top-bottom, right-left */
}
~~~