# Estlizando o slider

~~~css
/* BANNERS */
#banners-container {
    padding: 0;
}

.carousel-caption {
    bottom: 5em;
    padding: 1em;
    left: 12%;
    right: 12%;
}

.carousel-caption h5 {
    font-size: 1.8em;
}

@media(min-width: 768px) {
    #slider .carousel-item,
    #slider img {
        height: 600px;
    }

    .carousel-caption  {
        left: 23%;
        right: 23%;
    }

    .carousel-caption h5 {
        font-size: 4em;
    }
}

~~~