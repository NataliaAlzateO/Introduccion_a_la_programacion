<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


# Actividad: Diseñar un formulario de pedido de un producto

Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

Instrucciones:

 - Crear un nuevo documento HTML.
 - Crear un formulario con los siguientes campos:
 - Nombre del producto
 - Cantidad
 - Precio unitario
 - Precio total
 - Dirección de envío
 - Información de contacto (nombre, correo electrónico, número de teléfono)

Agregar los siguientes campos relacionados al formulario:

 - Método de pago
 - Fecha de entrega
 - Comentarios


Utilizar las etiquetas HTML apropiados para cada campo.

# SOLUCION

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <form action="">

        <h1>Formulario de pedido de un producto</h1>

        <br>

        <div>
            <label for="Nombre del Producto">Nombre del producto</label>
            <input type="text" name="Nombre del Producto" id="nombre">
        </div>

        <br>

        <div>

            <label for="Cantidad">Cantidad</label>
            <input type="number" name="Cantidad" id="Cantidad">

        </div>

        <br>

        <div>

            <label for="Precio Unitario">Precio Unitario</label>
            <input type="number" name="Precio Unitario" id="Precio">

        </div>

        <br>

        <div>
            <label for="Precio Total">Precio Total</label>
            <input type="number" name="Precio Total" id="Precio Total">

        </div>

        <br>

        <div>
            <label for="Dirección de envío">Dirección de envío</label>
            <input type="text" name="Dirección de envío" id="Direccion de envio">

        </div>

        <br>

        <h1>Información de contacto</h1>
        <br>

        <div>
            <label for="Nombre">Nombre Completo</label>
            <input type="text" name="Nombre" id="nombre">
        </div>

        <br>

        <div>
            <label for="email">Correo Electronico</label>
            <input type="text" name="email" id="Correo">
        </div>

        <br>

        <div>
            <label for="telefono">Numero de telefono</label>
            <input type="number" name="telefono" id="telefono">
        </div>

        <br>

        <h1>Metodo de pago</h1>

        <br>

        <div>

            <label for="Efectivo">Efectivo</label>
            <input type="radio" name="Efectivo" id="nombre">
            <br>
            <br>
            <label for="Transferecia">Transferecia</label>
            <input type="radio" name="Transferecia" id="nombre">
            <br>
            <br>
            <label for="Tarjeta de Credito">Tarjeta de Credito</label>
            <input type="radio" name="Tarjeta de Credito" id="nombre">
        </div>
        <br>
        <br>
        <label for="Enviar Pedido">Enviar Pedido</label>
        <input type="submit" name="Enviar" id="Pedido">
        <br>




    </form>

</body>

</html>

```





