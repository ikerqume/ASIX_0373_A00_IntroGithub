# ASIX_0373_A00_IntroGithub
Alberto apruébame porfa ;)

## HOLA 
### ADIOS

# Encabezado de nivel 1
## Encabezado de nivel 2
### Encabezado de nivel 3
#### Encabezado de nivel 4

*Texto en cursiva*  
**Texto en negrita**  
***Texto en negrita y cursiva***  
~~Texto tachado~~

Esto esta en __negrita__
Esto esta en **negrita**

Esto esta en _cursiva_
Esto esta en *cursiva*

__*TEXTO*__

1. ELEMENTO 1
* ELEMENTO 
2. ELEMENTO 2 
* ELEMENTO 
3. ELEMENTO 3
* ELEMENTO 


mfnsidfoisoifjioddsonPININIniefjifnsvicovjpiavrmcznivInvecsifioesfmiskvcniPEMIVNSONVOSINVLKnoiSFMWIORVNIOSN`pivrninvaoinsrfoinsvak


mfnsidfoisoifjioddsonPININIniefjifnsvicovjpiavrmcznivInvecsifioesfmiskvcniPEMIVNSONVOSINVLKnoiSFMWIORVNIOSN`pivrninvaoinsrfoinsvak


```
<p>Esto es un parrafo</p>
```

[LINK](https://www.google.com/?zx=1759402167197&no_sw_cr=1/ "TITULO DEL ENLACE")

![FOTONANO](./imagen1.jpg "FotoALONSO")


|NOMBRE|EQUIPO|POSICION|
|:-----------|:----------:|-----------:|
|MESSI|INTER MAIMI|MCO|
|PEDRI|FCB|MC|
|PAU CUBARSI|FCB|DFC|

COMANDO DE GIT PARA SUBIR COSAS A GITHUB
git init	Inicializa un nuevo repositorio
git add .	Añade todos los archivos al área de preparación
git commit -m "mensaje"	Guarda los cambios con un mensaje
git push origin main	Sube los cambios al repositorio remoto

HTML 

ESTRUCTURA 

```
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <title>Título de la página</title>
  </head>
  <body>
    <h1>Encabezado principal</h1>
    <p>Este es un párrafo.</p>
  </body>
</html>
```

<header>Encabezado de la página</header>
<nav>Menú de navegación</nav>
<main>Contenido principal</main>
<section>Sección de contenido</section>
<article>Artículo independiente</article>
<footer>Pie de página</footer>

```
<a href="pagina2.html">Ir a la segunda página</a>
<img src="imagen.jpg" alt="Descripción de la imagen" />
```
```
<table> 
  <tr> //row
    <th>Nombre</th> //encabezado
    <th>Edad</th>
  </tr>
  <tr>
    <td>Ana</td> //datos
    <td>22</td>
  </tr>
</table>
```
//esto es un comentario en html

FORMULARIO 

```
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ASIX-0373-IntroHTML</title>
</head>
    <body>
    <!--A continuación he puesto un encabezado -->
        <h1>Introducción HTML</h1>
    
        <p>Lorem</p><strong>Impus dolor</strong>

    <form action="URLdeDestino" method="POST">
        <label for="username">Username:</label>
        <input type="text" name="username" id="username" required>
        
        <br>

        <label for="realname">Nombre real:</label>
        <input type="text" name="realname" id="realname">
        <input type="radio" name="carnet" value="carnetsi">
    </form>

  <table border="1">
    <thead>
        <tr>
            <td>ORDEN</td>
            <td>ATLETA</td>
            <td>TIEMPO</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td >Dani</td>
            <td>03:51:02</td>
        </tr>
        <tr>
            <td rowspan="2">2</td>
            <td colspan="2">Juan</td>
        </tr>
        <tr>
            <td>Juan</td>
            <td>03:51:02</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td>ORDEN</td>
            <td>ATLETA</td>
            <td>TIMEPO</td>
        </tr>
    </tfoot>



    </table>
    <caption>Tabla </caption>

        <form action="URLdeDestino.html" method="GET">
            <label for="username">Username:</label>
            <input type="text" name="username" id="username" required>
            <br>
            <label for="realname">Nombre real:</label>
            <input type="text" name="realname" id="realname">
            <br>

            <fieldset>
                <legend>Carnet de conducir</legend>
                <label for="carnetsi">SI:</label>
                <input type="radio" name="carnet" value="carnetsi" id="carnetsi">
                <label for="carnetno">NO:</label>
                <input type="radio" name="carnet" value="carnetno" id="carnetno">
            </fieldset>
        <br>
            <fieldset>
                <legend>Gustos musicales</legend>
                <label for="pop">Pop:</label>
                <input type="checkbox" name="musica[]" value="pop" id="pop">
                <label for="heavy">Heavy:</label>
                <input type="checkbox" name="musica[]" value="heavy" id="heavy">
                <label for="pachanga">Pachanga:</label>
                <input type="checkbox" name="musica[]" value="pachanga" id="pachanga">
            </fieldset>
        <br>
        <label for="nacioniladidad">Nacionalidad:</label>
            <select name="Nacionalidad" id="nacioniladidad">
                <option value="españa">España</option>
                <option value="EEUU">EEUU</option>
                <option value="Uk">Uk</option>
                <option value="Japon">Japon</option>
            </select>
            <br>
            <label for="observaciones">Observaciones:</label><br>
            <textarea name="observaciones" id="observaciones" cols="25" rows="3" placeholder="Introduce aqui cualquier observacion que tengas"></textarea>
        <br>
            <button type="submit" name="Enviar" value="enviar">Enviar Datos</button>
        </form>
    </body>
</html>
```
