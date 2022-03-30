 ? PREGUTNAR SOBRE LOS CERTIFICADOS EN EL ENVIO DE LOS POST SUBMIT EN LOS formulario

emmet: automatically  create template html
+++++html
+++++head
+++++body
+++++h1,2,3,4,5,6
+++++p
+++++hr
+++++br: jump line
+++++span
+++++a
+++++img
+++++form: forma para recuperar informacion del usuario
 label -for
 +++++INPUT 
 >>-type: "submit (button), text, email,password,file,radio,>>checkbox" -id -name: el servidor lo usa como key -placeholder
 >>-value:los valores por defecto son 
 +++++TEXTAREA
 >valores por defecto: se insertan dentro de las dos etiquetas
 +++++SUBMIT:
 >toma todos los valores que se encuentra dentro del formulario
 a donde se va segun la ruta que uno tenga. "action="" method="GET""
 >el method get solo soporta hasta 255 caracteres
 +++++BUTTON
 > permite  insertar mas etiquetas dentro de ellos.
 >type:submit:envia los datos al servidor,button: no envia el formulario, el comportamiento se hace con javascript,reset: reseteara los controls
 > <!-- <input type="submit"></input> -->
      <button type="button">button usar con javascript</button>
      <button type="reset">reset controls</button>
      <button type="submit">submit values to server</button>

++++LISTAS
>ul: lista no ordenada
>ol: lista ordenada
>change the  number o dot  
><li style="list-style-type: lower-alpha">Sub Element 1</li>

++++TABLES
>thead: para agrupar elementos que se encuentran en la cabecera de la tabla
>tr:table row
>tr>th:table head (columns head)
>tr>td:defines a cell of a table that contains data (colums)
>tbody: para agrupar todas las filas que pertenencen al cuerpo de las tablas
>tfooter: para a gregar pie de pagina
+++IDENTIFICADOR
>id: atributo
>class: donde puede repetir
+++ESTRUCUTRA DE html body

<!DOCTYPE html>
<html lang="en">
<head>
  <title>Document</title>
</head>
<body>
  <header></header>
  <section>
  <article></article>
  </section>
  <footer></footer>
</body>
</html>


