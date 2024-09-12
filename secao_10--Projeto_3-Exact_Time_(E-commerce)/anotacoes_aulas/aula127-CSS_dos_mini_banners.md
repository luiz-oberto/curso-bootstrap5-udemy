# CSS dos mini banners

~~~css
/* MINI BANNERS */
#mini-banners {
    margin-top: -3em;
    /* altera o posicionamento no eixo z (profundidade) */
    z-index: 10;
}

#mini-banners .col-12 {
    z-index: 1;
    height: 300px;
    padding: 1.5em;
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

@media(min-width: 768px) {
    #mini-banners .col-12 {
        max-width: 30%;
    }
}

#mini-banners .col-12 h2 {
    text-transform: uppercase;
    max-width: 50px;
    font-size: 2.2em;
    font-weight: 700;
    line-height: 1em;
}

#mini-banners .col-12 img {
    height: 220px;
    position: absolute;
    right: 1em;
    bottom: 1em;
}

#mini-banners .col-12 a {
    font-weight: bold;
    color: #fff;
    font-size: 0.8em;
    transition: 0.5s;
}

#mini-banners .col-12 a:hover {
    color: #101010;
}

#mini-banners .col-12 a:hover {
    color: #101010;
}

#mini-banners #mini-banner-1 a:hover,
#mini-banners #mini-banner-3 a:hover {
    color: #C09578;
}

#mini-banners #mini-banner-3 a {
    color: #101010;
}

~~~