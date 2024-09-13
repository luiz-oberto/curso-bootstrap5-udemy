# Galeria de imagens

~~~~html
    <!-- GALERIA -->
    <div class="container-fluid" id="gallery">
        <div class="row">
            <div class="col-6 col-md-2 image-container" id="insta1"></div>
            <div class="col-6 col-md-2 image-container" id="insta2"></div>
            <div class="col-6 col-md-2 image-container" id="insta3"></div>
            <div class="col-6 col-md-2 image-container" id="insta4"></div>
            <div class="col-6 col-md-2 image-container" id="insta5"></div>
            <div class="col-6 col-md-2 image-container" id="insta6"></div>
        </div>
    </div>
~~~~


~~~~css
/* GALERIA */
#gallery .image-container {
    background-size: cover;
    background-position: center;
    height: 225px;
    cursor: pointer;
    transition: .5s;
    border: 3px solid #101010;
}

#gallery .image-container:hover {
    border-color: #C09578;
}

#insta1 {
    background-image: url('../img/insta1.jpg');
}

#insta2 {
    background-image: url('../img/insta2.jpg');
}

#insta3 {
    background-image: url('../img/insta3.jpg');
}

#insta4 {
    background-image: url('../img/insta4.jpg');
}

#insta5 {
    background-image: url('../img/insta5.jpg');
}

#insta6 {
    background-image: url('../img/insta6.jpg');
}
~~~~