# CSS dos links do footer

~~~css
/* FOOTER */
#footer-links-container {
    border-bottom: 1px solid #626262;
}

#footer .footer-column {
    padding: 2em;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
}

@media(min-width:  768px) {
    #footer .footer-column {
        padding: 5em 2em;
    }
}

#footer-links-container h3 {
    margin-bottom: 25px;
    text-transform: uppercase;
}

#footer-links-container li {
    font-size: 0.8em;
    text-align: center;
}

@media(min-width:  768px) {
    #footer-links-container li {
        text-align: left;
    }
}

#footer-links-container a {
    text-decoration: none;
}

#footer-links-container a:hover {
    color: #C09578;
}

#footer-center {
    border-left: 1px  solid #626262;
    border-right: 1px solid #626262;
}

#footer-center h3{
    font-weight: 900;
}

#footer-center .store-phone {
    color: #C09578;
    font-weight: bold;
    font-size: 2em;
    margin-top: -15px;
}
~~~