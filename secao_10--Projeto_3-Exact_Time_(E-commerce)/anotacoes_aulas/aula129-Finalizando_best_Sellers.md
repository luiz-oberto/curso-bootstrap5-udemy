# Finalizando Best Sellers

~~~~css
/* BEST SELLERS */
#best-sellers {
    /* isso dá uma espaçamento em cima e em baixo */
    padding: 4em 0;
}

#best-sellers .row {
    margin: 0;

}

#best-sellers .col-md-3 {
    padding: 0;
}

.title {
    text-transform: uppercase;
    font-weight: 900;
    font-size: 2.5em;
    margin-bottom: 1em;
    text-align: center;
}

@media (min-width: 768px) {
    .title {
        text-align: left;
    }
}

.card {
    text-align: center;
    border-radius: 0;
}

.card img {
    width: 140px;
    margin: 2em auto;
}

.card .card-category {
    font-size: 0.8em;
}

.card .card-text {
    margin: 2em 0;
    font-weight: bold;
}

.btn {
    background-color: transparent;
    border-color: #C09578;
}

.btn:hover {
    background-color: #C09578;
    border-color: #C09578;

}
~~~~