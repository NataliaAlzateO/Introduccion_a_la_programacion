<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


# Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5

Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

 - 4 Imagenes
 - 2 Videos
 - 4 Audios
 - 2 Inline Frame

```html
 
Utiliza encabezados para títulos en cada elemento (<h1>...<h6>).

Crea una descripción para cada elemento utilizando párrafos (<p>).

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

Usa <strong> para resaltar texto importante.
Utiliza <br> para insertar saltos de línea si es necesario.
Agrega <span> para aplicar estilos específicos a porciones de texto.
Emplea <i> para enfatizar o dar énfasis a palabras o frases.
Utiliza <u> para subrayar texto cuando sea necesario.
Considera el uso de <div> para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.

```
# SOLUCION

```html
<!DOCTYPE html>
<html>

<head>
    <title>CROMOSOMA 21</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>CROMOSOMA 21</h1>
        <h3>No eres lo que logras, eres lo que superas</h3>
    </header>

    <section>
        <h2>Imágen1</h2>
        <h1>Conozcamos un poco del Sindrome de down</h1>
        <p><strong>El síndrome de Down</strong> es una afección en la que la persona tiene un cromosoma extra. Los
            cromosomas son pequeños “paquetes” de genes en el organismo. Determinan cómo se forma el cuerpo del bebé
            durante el
            embarazo y cómo funciona mientras se desarrolla en el vientre materno y después de nacer.</p>

        <center><img src="IMSGEN1.jpg" alt="" width="400"></center>

        <h2>Imágen2</h2>

        <center><img src="child-1725120_640.jpg" alt="" width="400"></center>

        <h2>Vamos a estudiar</h2>
        <p>El inicio de la vida escolar representa un reto personal y un proceso individual para cada niño. <u><i>Su
                    capacidad de adaptación</i></u> dependerá de múltiples factores, que van desde el contexto familiar
            en el que ha crecido, hasta las habilidades básicas que haya desarrollado durante el mismo periodo de
            tiempo. Esta etapa
            preescolar es entonces un momento clave en el aprendizaje de los niños y niñas, pues además de forjar la
            base de sus intereses, juegos, competencias,<strong><span style="color: rgb(219, 111, 22);"> habilidades
                    sociales y demás herramientas que lo ayudarán a
                    desenvolverse durante su vida.</span></strong></p>

        <img src="kids-2639869_640.jpg" width="200">

        <h2>Imágen4</h2>

        <img src="nathan-anderson-J3Xjyg5m8kY-unsplash.jpg" alt="" width="300">


    </section>

    <section>
        <h2>Video 1</h2>
        <video src="bebe.mp4" controls width="500"></video>

        <h2>Video 2</h2>
        <video src="niños estudiando.mp4" controls width="500"></video>

    </section>

    <section>
        <h2>Audio 1</h2>
        <p>Celestial</p>
        <audio src="celestial.mp3" controls></audio>

        <h2>Audio 2</h2>
        <p>Cerebro</p>
        <audio src="cerebro.mp3" controls></audio>

        <h2>Audio 3</h2>
        <p>Nos relajamos</p>
        <audio src="relajación.mp3" controls></audio>

        <h2>Audio 4</h2>
        <p>¡Y que tal esto!</p>
        <audio src="piano.mp3" controls></audio>

    </section>

    <section>
        <h2>iFrames</h2>
        <p><Strong>UN POCO DE CONOCIMIENTO</Strong></p>
        <iframe
            src="https://diariodelhuila.com/el-172-de-ninos-en-colombia-nace-con-sindrome-de-down-como-lograr-la-inclusion-escolar/"
            width="500"></iframe>

        <h2>iFrames</h2>
        <p>DEPORTE</p>
        <iframe
            src="https://elpais.com/mamas-papas/expertos/2023-04-01/deporte-inclusivo-y-sindrome-de-down-el-mejor-camino-para-normalizar-las-capacidades-diferentes-en-ninos-y-adolescentes.html"
            width="500"></iframe>


    </section>

    <footer>
        NATAIA MARIA ALZATE OTALVARO
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```


