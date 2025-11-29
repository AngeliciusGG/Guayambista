* {
    padding: 4px;
    margin: 0;
    box-sizing: border-box;
}

/* paleta de colores
'big-stone': {
    '50': '#f5f7fa',
    '100': '#eaeef4',
    '200': '#d0dbe7',
    '300': '#a6bcd3',
    '400': '#7799b9',
    '500': '#557ca2',
    '600': '#426287',
    '700': '#37506d',
    '800': '#30455c',
    '900': '#2c3c4e',
    '950': '#1f2937',
}, */
body {
    background-color: #1f2937;
}

header {
    background-image: url(Imagenes/Plaza-complejo-rio-guayamba/foto\ complejo\ desde\ la\ pasarela.jpeg);
    background-position: center;
    background-size: cover;
    padding: 8px;
    border-radius: 10px;
    width: 100%;
}

.logo-titulo-subitulo {
    display: flex;
    flex-wrap: wrap;
}

.tituloh1 {
    font-size: 2.4rem;
    font-style: oblique;
    color: white;
}

.subtituloh1 {
    font-size: 1.2rem;
    font-weight: bold;
    color: white;
}

.logo-header {
    height: 120px;
    border-radius: 50%;
}

/* Estilos sección presentacion y mapas descargables*/
.presentacion {
    background-color: #2c3c4e;
    border-radius: 6px;
    padding: 0.6rem;
}

.mapa_descargable {
    background-color: #d0dbe7;
    color: #1f2937;
    border: solid 2px black;
    text-decoration: none;
    font-weight: bold;
    border-radius: 6px;
    padding: 0.6rem;
    margin-top: 1rem;
    margin-bottom: 1rem;
}

.mapa-guayamba {
    border: solid 2px #7799b9;
    border-radius: 6px;
    margin-top: 1.1rem;
    background-image: url(Imagenes/Plaza-complejo-rio-guayamba/Río\ Guayamba\,\ vista\ desde\ la\ pasarela\ hacia\ el\ río.jpg);
    background-size: cover;
    height: 500px;
}

.pdf-mapa {
    margin: 1rem;
}

.pdf-mapa h3 {
    margin-bottom: 1rem;
}

.referencia-mapa {
    background-color: #7799b9;
    border-radius: 6px;
}

.texto-referencia-mapa p {
    background-color: #7799b9;
    border-radius: 6px;
    color: #1f2937;
    margin: 0.8rem;
    display: inline-block;
    font-weight: bold;
    font-size: 0.9rem;

}

.texto-referencia-mapa p {
    margin: 6px;
}

.titulo-mapa {
    color: black;
    background-color: #7799b9;
    font-size: 1.4rem;
    border-radius: 6px;
}

.parrafo-qr,
.titulo-qr {
    font-size: 18px;
    font-weight: bold;
    /* color: #d0dbe7; */
    background-color: #7799b9;
    color: black;
    border-radius: 6px;
    display: inline-block;
    width: 55%;
}


a:hover {
    background-color: #1f2937;
    color: #d0dbe7;
    border: solid 2px #d0dbe7;
    cursor: pointer;
    box-shadow: 4px 4px 3px #7799b9;
    transition: background-color ease-out 0.3s, color ease-out 0.3s, border ease-out 0.3s;
}

.presentacion-titulo-y-subtitulo {
    text-align: center;
    color: white;
    /* background-image: url(Imagenes/Plaza-complejo-rio-guayamba/Río\ Guayamba\,\ vista\ desde\ la\ pasarela\ hacia\ el\ río.jpg); */
    background-size: cover;
}

/* .descripcion-titulo{
    color: black;
} */
.presentacion-titulo-y-subtitulo h3 {
    color: white;
}

.presentacion-titulo {
    padding: 1rem;
    /* color: black; */
}

/* qr y mapa descargable*/
.qr-mapas-descargable {
    text-align: center;
}

/* Estilo zonas de interés: divs, img, titulos, subtitulos.*/
.zonas-de-interes {
    background-color: #2c3c4e;
    border-radius: 6px;
}

.division-de-zonas div {
    background-color: #36454F;
    /* border: solid 2px black; */
    border-radius: 6 px;
    margin: 6px;
}

.referencia {
    background-color: white;
    /* border: solid 2px black; */
    border-radius: 6px;
    padding: 1rem;
}

.turismo-info-productos-historia {
    background-color: #2c3c4e;
    border-radius: 6px;
    text-align: center;
}

.turismo-info-productos-historia h3 {
    color: #d0dbe7;
    padding: 6px;
}

.img-referencia {
    max-width: 80%;
    border-radius: 10px;
    text-align: center;
    display: block;
    margin: 0 auto;
}

.texto-referencia {
    color: #d0dbe7;
    font-style: italic;
    font-size: 1.33rem;
    text-align: center;
    /* text-decoration: underline; */
}

.titulo-referencia {
    background-color: #d0dbe7;
    text-align: center;
    font-size: 1.2rem;
}

.actividades-servicios {
    background-color: #37506d;
    border-radius: 6px;
    margin-top: 8px;
}

.titulo-servicio {
    background-color: #7799b9;
    border-radius: 6px;
    border: solid 2px black;
}

/* accesos rapidos */
.presentacion-accesos-rapidos {
    background-color: #7799b9;
    border: solid 2px black;
    border-radius: 6px;
}

.numeros-servicios {
    text-align: center;
    background-color: #2c3c4e;
    border-radius: 6px;
    padding: 0.8rem;
}

.servicios-prioritarios {
    background-color: #37506d;
    border: solid 2px black;
    margin: 0.6rem;
    border-radius: 6px;
    padding: 0.8rem;
}

.tipo-de-servicio {
    background-color: #7799b9;
    border-radius: 6px;
    border: solid 2px black;
}

.tipo-de-servicio p h5 {
    margin: 1rem;
}

.tipo-de-servicio p {
    color: #d0dbe7;
}

/* estilo para el footer
 */
footer {
    background-color: #2c3c4e;
    /* border-radius: 6px; */
    color: black;
    display: flex;
    background-image: url(Imagenes/img-zonas-turisticas/La\ olla.jpg);
    background-position: center;
    background-size: cover;

}

.img_footer {
    height: 100px;
    border-radius: 50%;
}

@media screen and (min-width:700px) {
    header {
        height: 350px;
        background-position: center;
        background-size: none;
        max-width: 90%;
        margin: 0 auto;
    }

    .presentacion-titulo {
        font-size: 1.8rem;
    }

    .descripcion-titulo {
        font-size: 1.5rem;
    }

    #seccion-principal {
        margin: 0 auto;
        display: flex;
        justify-content: center;
        align-items: center;
        width: 80%;
    }

    .referencia-mapa {
        display: block;
        width: 60%;
        margin: 0 auto;
    }

    .titulo-referencia {
        display: block;
        width: 75%;
        margin: 0 auto;
        border-radius: 6px;
        padding-top: 8px;
    }

    /*  .referencia-imagen-texto{
        display: flex;
        flex-wrap:wrap;
    } */
    .texto-referencia {
        padding: 10px;
    }

    /* Estilo zonas de interés */
    .referencia {
        display: flex;
        height: auto;
        flex-wrap: wrap;
    }

    .contenedor-de-descripcion {

        flex: 1 1 250px;
    }

    .img-referencia {
        min-width: 250px;
    }

    /* Estilo contenedor numeros telefónicos */

    .presentacion-accesos-rapidos {
        margin: 0 auto;
        width: 96%;
    }

    .contenedor-servicios-prioritarios {
        display: flex;
    }

    .servicios-prioritarios {
        flex-grow: 1;
    }

    .tipo-de-servicio {
        font-size: 18px;
        font-weight: bold;
    }

    .servicios-prioritarios h5 {
        font-size: 16px;
    }

    /* estios footer */
    .titulo-footer {
        font-size: 20px;
        font-weight: bold;
    }

    .texto-footer {
        font-size: 20px;
    }
}

@media screen and (min-width:1000px) {
    header {
        width: 100%;

    }
        .division-de-zonas {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
    }

    .contenedor-referencia-de-zonas {
        flex: basis 48%;
        margin-bottom: 20px;
        flex-grow: 0;
    }
    .referencia{
        display: flex;
    }
    .contenedor-de-descripcion{
        flex-direction:column ;
    }
}
