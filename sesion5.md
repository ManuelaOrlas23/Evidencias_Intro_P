<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 
```
<!DOCTYPE html>
<html lang="en">
<head>

    <style>
        h1 {
            text-align: center;
            font-size: 24px;
            font-weight: bold;
            margin-top: 40px;
            margin-bottom: 10px;
        }

        p {
            text-align: center;
        }
        h2 {
            text-align: left;
            font-size: 24px;
            font-weight: bold;
            margin-top: 40px;
            margin-bottom: 10px;
        }

        p {
            text-align: left;
        }
       
        img {
            display: block;
            margin: 0 auto;
            max-width: 300%;
            width: 400px;
            margin-bottom: 40px;
        }
        img {
            display: block;
            margin: 0 auto;
            max-width: 300%;
            width: 400px;
            margin-bottom: 40px;
        }
        footer {
            background-color:#5533FF;
            color:black;
            padding: 10px;
            text-align: center;
        }
    body{
        background-color: palevioletred;
    }

    </style>    
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sesión5 Formularios</title>
</head>
<body> 
    <h1>Supermercado Orlas</h1>
    <img src="Imagen/Supermercado.jpg" width="5000" aling="center">
    <form action="example.php" method="post">
       <div> 
        <h2>Datos del pedido</h2>
        <label for="nombre del producto">Nombre del producto:</label>
        <input type="text" name="nombre del producto" id="nombre del producto" placeholder="Nombre del producto">
    </div>

    <br />

    <div>

        <label for="Cantidad">Cantidad:</label>
        <input type="number" name="Cantidad" id="Cantidad" placeholder="Cantidad">
    </div>

    <br />
    <div>

        <label for="Precio Unitario">Precio Unitario:</label>
        <input type="size" name="Precio Unitario" id="Precio Unitario" placeholder="Precio Unitario">
    </div>

    <br />

    <div>
        <label for="Precio Total">Precio Total:</label>
        <input type="size" name="Precio Total" id="Precio Total" placeholder="Precio Total">
    </div>

   <br />

    <div>
        <img src="Imagen/Persona.jpg" width="5000" aling="center">
        <h3>Informacion de contacto</h3>
        <label for="Nombre Completo">Nombre Completo:</label>
        <input type="text" name="Nombre" id="Nombre Completo" placeholder="Nombre Completo">
    </div>

    <br />
    
    <div>
        <label for="idCorreo Electronico">Correo Electronico:</label>
        <input type="email" name="Correo Electronico" id="Correo Electronico" placeholder="Correo Electronico">
    </div>

    <br />

    <div>
        <label for="Metodo de pago">Metodo de pago:</label>     
    </div>

    <br />

    <div>
        <label for="Efectivo">Efectivo</label>
        <input type="radio" name="Efectivo" value="Efectivo" id="Efectivo" />
    </div>

    <br />

    <div>
        <label for="Trajeta">Tarjeta</label>
        <input type="radio" name="Tarjeta" value="Tarjeta" id="Tarjeta" />
    </div>

    <br />
    <div>
        <input type="datetime-local" name="Fecha y hora" id="" />
    </div>

    <br/>
    <div>
        <div>
            <label for="comentario">Comentario</label>
            <textarea name="comentario" id="comentario" cols="30" rows="10" minlength="50"
                maxlength="100"></textarea>
        </div>
    </div>

    <br />
        <input type="submit" value="Enviar">
      </form>
      <footer>
        Manuela Orlas Rengifo
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

<!-- Su documentación aquí -->






