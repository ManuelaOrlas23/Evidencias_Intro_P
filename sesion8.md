<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 

## Actividad: Aplicando estilos con selectores CSS
El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

- Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado <header>
- Tres párrafos <p>
- Una imagen <img>
- Un pie de página <footer>

Aplica los siguientes estilos usando selectores de etiqueta:

- Color rojo a los encabezados <h1>
- Color azul a los párrafos <p>
- Borde grueso negro a la imagen <img>

Aplica los siguientes estilos usando seleccionadores de clase:

- Color verde a los elementos con la clase ".destacado"
- Tamaño de fuente grande a los elementos con la clase ".grande"
- Aplica los siguientes estilos usando seleccionadores de ID:

- Color amarillo al elemento con ID "#principal"
- Sombra al elemento con ID "#sombras"

-Aplica los siguientes estilos usando seleccionadores descendientes:

- Color gris a los párrafos dentro de un <div>
- Centrar el contenido de la sección <section>

## Desarrollo 
'''

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi pagina web</title>
    <style>
        h1{
            color: red;
        }
        p{
            color: blue;
        }
        .destacado {
      font-size: 30px;
      color: green;
    }
    .grande{
        font-size: 90px;
    }
    #principal{
        color: yellow;
    }
    #sombras{
        text-shadow: 10px 15px 10px black;
    }
    </style>
</head>
<body>
    <h1>Hola Mundo</h1>
    <h1 class="destacado">Bienvenidos a mi pagina de perros</h1>
    <p id="principal">Las mejores fotos de perros lo encuentras acá</p>
    <p id="sombras">Acá encontraras imagenes sobre perros tiernos</p>
    <p class="grande">Espero te gusten mis imagenes</p>
    <img src="Img/original.jpg" style="border: 10px solid black; border-radius: 20% / 30%;">

    <footer style="background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;">
        Manuela Orlas
        <br />
        <br />
        CESDE
        <br />
        <br />
        &copy;2023
     </footer>
</body>
</html>

'''
<!-- Su documentación aquí -->






