<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


# Actividad: Aplicando estilos con selectores CSS
El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

 - Encabezado <header>
 - Tres párrafos <p>
 - Una imagen <img>
 - Un pie de página <footer>
 
 Aplica los siguientes estilos usando selectores de etiqueta:

```html 
 - Color rojo a los encabezados <h1>
 - Color azul a los párrafos <p>
 - Borde grueso negro a la imagen <img>

```
Aplica los siguientes estilos usando seleccionadores de clase:

 - Color verde a los elementos con la clase ".destacado"
 - Tamaño de fuente grande a los elementos con la clase ".grande"
 
 Aplica los siguientes estilos usando seleccionadores de ID:

 - Color amarillo al elemento con ID "#principal"
 - Sombra al elemento con ID "#sombras"

Aplica los siguientes estilos usando seleccionadores descendientes:

```html
 - Color gris a los párrafos dentro de un <div>
 - Centrar el contenido de la sección <section>
```

# SOLUCION

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1 {
            color: red;

        }

        p {
            color: blue;
        }

        div p {
            color: grey;
        }

        section {
            text-align: center;
        }

        .grande {
            font-size: 80px;
        }

        .destacado {
            color: green;
        }

        #principal {
            color: yellow;
        }
    </style>


    <header>
        <h1 class="grande">¿Por qué desde septiembre se siente diciembre? </h1>
    </header>

    <section>
        <p id=>Apenas van 20 días de septiembre y en los almacenes ya están vendiendo árboles, adornos y
            luces de Navidad,
            eso sin olvidar que desde el primer día de este mes en la radio suena el estribillo “Desde septiembre se
            siente dicieeembre”.</p>

    </section>
    <h1 id="principal">UNA FELIZ NAVIDAD</h1>

    <p class="destacado">En el popular sector comercial del Hueco, en el Centro de Medellín, ya están a la venta los
        juguetes para el
        traído del Niño Jesús y la ropa para el “estrén”, mientras que las agencias de viaje ya están vendiendo
        planes de vacaciones de fin de año.</p>
    <div>
        <p> Lo cierto es que ese afán extender la celebración de diciembre por cinco meses, de septiembre a enero, tiene
            sus razones que van desde lo comercial hasta lo sociológico y emocional.</p>
    </div>

    <section>
        <img src="https://estaticos.elcolombiano.com/binrepository/867x565/88c0/780d565/none/11101/QJTJ/whatsapp-image-2023-09-21-at-2-49-40-pm-3_43333479_20230921151145.jpg"
            width="500" height="300" style="border: 1px solid black;">
    </section>


    <br>
    <br>
    <footer>
        <p style="box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.5);">Diciembre está asociado con una celebración
            judiocristiana muy antigua y popular en el mundo occidental. FOTO
            Manuel Saldarriaga.</p>
    </footer>



</html>
```






