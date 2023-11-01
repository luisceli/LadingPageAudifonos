html{
    box-sizing: border-box;
    font-size: 62.5%;
}
*, *:before,*:after{
    box-sizing: inherit;;
}

Establece el modelo de caja "border-box" para todos los elementos HTML, lo que significa que el tamaño total de un elemento incluye el contenido, el padding y el borde, facilitando el control del diseño.
Define un tamaño de fuente base del 62.5% del tamaño predeterminado del navegador (equivalente a 10 píxeles) para simplificar el manejo de tamaños de fuente en el documento.
Hereda el modelo de caja "border-box" a los elementos y a sus pseudo-elementos (::before y ::after), asegurando consistencia en todo el diseño del documento.




******************************
base para cualquier proyecto
:root{
    --colorPrimario:#1073ba;
    --colorSecundario:#00da55;
    --colorGris:#3b3b3b;
    --colorBlanco:#ffffff;
    --colorNegro:#1f1e1e;
    --colorGrisClaro:#e1e1e1;

    --separacion:5rem;
    --fuentePrincipal:'Roboto',sans-serif;
    --fuenteSecundaria:'Lato',sans-serif;
}

html{
    box-sizing: border-box;
    font-size: 62.5%;
}
*, *:before,*:after{
    box-sizing: inherit;;
}
body{
    font-family: var(--fuentePrincipal);
    font-size: 1.6rem;
    line-height: 1.5;
}

/* globales */
.contenendor{
    max-width: 120rem;
    width: 90%;
    margin: 0 auto;
}
h1,h2,h3{
    font-family: var(--fuenteSecundaria);
    font-weight: 900;
    margin: calc( var(--separacion)/2 ) 0;
}
h1{
    font-size: 4.4rem;
}
h2{
    font-size: 3.6rem;
}
h3{
    font-size: 2.8rem;
}
img{
    max-width: 100%;
    display: block;
}
/* utilidades */
.text-center{
    text-align: center;
}


******************************************* para detectar que soporta en la imagenes*********************
https://gist.github.com/codigoconjuan/3bbdf0f2920cd9c65187128dd1c032cc
