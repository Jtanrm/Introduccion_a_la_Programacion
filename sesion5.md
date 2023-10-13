<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->

## Actividad: Diseñar un formulario de pedido de un producto.

Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

Instrucciones:

1. Crear un nuevo documento HTML.
2. Crear un formulario con los siguientes campos:

* Nombre del producto
* Cantidad
* Precio unitario
* Precio total
* Dirección de envío
* Información de contacto (nombre, correo electrónico, número de teléfono)
* Agregar los siguientes campos relacionados al formulario:
* Método de pago
* Fecha de entrega
* Comentarios
* Utilizar las etiquetas HTML apropiados para cada campo.
  
## DESARROLLO 

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
    <title>Document</title>
</head>

<body>
    <h1>Producto</h1>
    <form>FORMULARIO</form>
    
    <div>
        <label for="idNombre del producto">Nombre del producto</label>
        <input type="text" id="idNombre del producto" >
    
    </div>
    <br>
    
    <div>
        <label for="idCantidad">Cantidad</label>
        <input type="number" id="idCantidad" >
    
    </div>
    <br>
    <div>
        <label for="idPrecio unitario">Precio unitario</label>
        <input type="number" id="idPrecio unitario" >
    
    </div>
    <br>
    
    <div>
        <label for="idPrecio total">Precio total</label>
        <input type="number" id="idPrecio total" >
    
    </div>
    <br>
    
    <div>
        <label for="idDirección de envío">Dirección de envío</label>
        <input type="text" id="idDirección de envío" >
    
    </div>
    <br>
    
    <div>
        <h1><span style="color: rgb(0, 0, 0);"</span>Información de contacto</h1>
        <label for="idNombre">Nombre</label>
        <input type="text" id="idNombre" >
    
    </div>
    <br>
    
    <div>
       
        <label for="idCorreo electronico">Correo electronico</label>
        <input type="email" id="idCorreo electronico" >
    
    </div>
    <br>
    
    <div>
       
        <label for="idNúmero de telefono">Número de telefono</label>
        <input type="text" id="idNúmero de telefono" >
    
    </div>
    <br>
    
    
    
    <div>
        <h1><span style="color: rgb(0, 0, 0);"</span>Metodo de pago</h1>
        <label for="idTarjeta debito">Tarjeta debito</label>
        <input type="radio" id="idTarjeta debito" >
    
    </div>
    <br>
    <div>
        <label for="idTarjeta credito">Tarjeta credito</label>
        <input type="radio" id="idTarjeta credito" >
    
    </div>
    <br>
    <div>
        <label for="idTransferencia">Transferencia</label>
        <input type="radio" id="idTransferencia" >
    
    </div>
    <br>
    <div>
        <label for="idEnviar pedido">Enviar pedido</label>
        <input type="submit" id="idEnviar pedido" >
    </div>
    

    
        </form>
    
    
</body>

</html>


![](image-26.png)


[Siguiente](./sesion6.md)
